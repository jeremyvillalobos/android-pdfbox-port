android-pdfbox-port
===================

A port of PdfBox 1.8 to the Android platform.

This is (will eventually be) a port of pdf-box 1.8 to Android.

Road Map

If you are interested in the project, please sign up.  This is just starting and we are interested to know what type of audience it will get.

Because Android is based on Java, the port is fairly easy with some challenges:

Security:  PdfBox using BouncyCastle.  Android uses a reduced set of functionality from BouncyCastle.  On this implementation we use (will) SpongyCastle, which is a complete port of BouncyCastle to Android.

Images: The images libraries from Java must be replaced with Android equivalents.

Graphics2D:  The graphics 2D object must be replaced with Android canvas.

Core Java:  Some Apache Harmony is (will) used to retain some Java functionality.


This component will be part of 
PDF-to-Speech Pro
https://play.google.com/store/apps/details?id=com.practicalapps&hl=en
