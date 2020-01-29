## Face recognition system with FaceNet

In this project we built a face recognition system; concepts are from FaceNet. 

### Face recognition problems commonly fall into two categories:

 - Face Verification - "is this the claimed person?". For example, at some airports, we can pass through customs by letting a system scan the passport and then verifying that the person is actually what he claims to be. A mobile phone that unlocks using our face is also using face verification. This is a 1:1 matching problem.

 - Face Recognition - "who is this person?". For example, employees entering their office without needing to otherwise identify themselves. This is a 1:K matching problem. 

 - FaceNet learns a neural network that encodes a face image into a vector of 128 numbers. By comparing two such vectors, we can then determine if two pictures are of the same person. We implemented the triplet loss function in this project.
