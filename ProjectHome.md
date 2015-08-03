MEOS2 is an open source Android Java Proof of Concept of an OCR function for reading the Machine Readable Zone from a Travel Document. The POC has been realized by Novay (http://www.novay.nl) and myself for the Dutch Police.

The Application automatically reads the MRZ from a camera image and give the result back to the user.

Because it is just a Proof of Concept the application is only tested on a Samsung S4 and S4 mini.

For the OCR part the Android implementation of Tesseract 3.0.2 is used, better known as Tess-two. For the image filters we used the Leptonica and imageJ Library and ported the relevant filters to Android.