Libraries used : 

QR-Code Generator -> https://www.nayuki.io/page/qr-code-generator-library

Tiny -PNG-Out -> https://www.nayuki.io/page/tiny-png-output

---How to run--- 

In WSL ubuntu for windows or in a Linux based system:

->sudo apt-get update

->sudo apt-get install cmake


Go to the build folder:

->cd build


To compile the code:

->cmake ..

->make all


To run the code:

->cd src

->./qr-to-png


This will create 4 png files with the qr codes of varying sizes
