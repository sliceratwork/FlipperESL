# FlipperESL
**This WIP and as of now I have not tested it myself**
Modified files from furrtek's PrecIR code to output a **.ir** file for use on a Flipper Zero.

Original files: https://github.com/furrtek/PrecIR

## Usage
Run img2ir.py with the following arguements: 
* 1. Name for the .ir file that will be generated. 
* 2. Image file name of image to be converted (208x102 pixels or less)
* 3. Barcode number of your ESL. You can either read the code on the back or scan the barcode using an app on your phone.
* 4. Page number of the page number to update on the ESL (0~15)

A **.ir** file will be generated that can be uploaded to a Flipper Zero through qFlipper.

*Note that imageio python package is required to run the code*
