# DigitalAttendanceSystem
Digital Attendance System Based on a Group Photo

Our project is divided into two parts. First, we tried to de-
ploy a basic Principal Component Analysis combined
with a support vector machine framework to create a
setup that recognizes human faces from a photograph and
can be used as an attendance marking system. We work
on the AT&T dataset which consists of 40 individuals, each
having 10 fully frontal images. The size of each image is
112 × 92 and all images are in grayscale.
The second part involves detection of faces from an input
images once the PCA + SVM framework is complete. For
this we had to use transfer learning methods in opencv
and dlib libraries. Both have simple pre trained detectors
called harr cascade and frontal face detector. We used
this to detect faces from an given input image and store it
in a folder.
