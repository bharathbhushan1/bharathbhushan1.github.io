---
layout: post
title:  "Tensorflow — Order of fetches"
date:   2016-11-21 10:00:00 +0000
categories: machine learning
tags: [machine learning, tensorflow]
---

I am playing with Tensorflow and found this interesting effect. The following code fragment gives different results each time you run it.

    tf.reset_default_graph()
    state = tf.Variable(2.0, name=”state”)
    one = tf.constant(1.0, name=”one”)
    update = tf.assign(state, tf.add(state, one))
    init = tf.initialize_all_variables()
    with tf.Session(config=config) as sess:
      sess.run(init)
      result = sess.run([update, state])
      print(result)
      result = sess.run([update, state])
      print(result)
    
    [3.0, 2.0]
    [4.0, 3.0]
    [3.0, 2.0]
    [4.0, 4.0]

