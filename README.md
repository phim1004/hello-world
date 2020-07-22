# hello-world
import tensorflow as tf
tf._versioin_
'1.0.0'

tutorial repository
hello = tf.constant("Hello, TensorFlow!")

#seart a TF session
sess = tf.Session()

#run the op and get result
print(sess.run(hello))

node1 = tf.constant(3.0, tf.float32)
node2 = tf.constant(4.0)
node3 = tf.add(node1, node2)

print("node1:", node1, "node2:", node2)
print("node3:", node3)

sess = tf.Session()
print("sess.run(node1, node2):", sess.run([node1, node2]))
print("sess.run(node3):", sess.run(node3))
