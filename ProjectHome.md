The system tries to match a given face image to a set of given face images using a number of eigenfaces .It implements the algorithm developed by M.Turk and Pentland.A build.xml is included in the archive.Unzip the archive to a directory and run ant.

A number of targets are given in the build.xml to run the program using different images and different values for the number of eigenfaces to be used in face recognition.

caveat:
This project is not optimized for production use.It was done out of academic curiosity..so make sure that your machine is big enough for a huge cache file if you are using large number of big images :-)