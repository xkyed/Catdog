# Catdog
session_conf = tf.ConfigProto(
      intra_op_parallelism_threads=1,
      inter_op_parallelism_threads=1)
sess = tf.Session(config=session_conf)

K.set_session(sess)

Data 
Training
333 Files each 

Validation
167 Files each
