# Andoy-Onion-Checker

This is a github repo for the ai side of an ESP32 cam that detects onion disease or whatever it is.

## Setup

Before doing anything go to the [ESP32CAM Library](https://github.com/yoursunny/esp32cam) and download it to Zip.

After downloading the Zip, Go to Arduino IDE and import the library. To do that, go to the Arduino -> Sketch -> Include Library -> Add ZIP Library. Look for the new ZIP file.

After doing that, Install python. Any python will do.

Next step is to install NumPy and OpenCV. Use Pip.

```bash
pip install numpy

pip install opencv-python
```

Thats the setup!

## How to use?

Open Arduino IDE and copy paste andoybayot.ino. And please, read the fucking code.

Simply compile and upload. During uploading make sure to:

1.Make sure the IO0 pin is shorted with the ground when you have pressed the upload button.

2.If you see the dots and dashes while uploading press the reset button immediately

3.Once the code is uploaded, remove the I01 pin shorting with Ground and press the reset button once again.

4.If the output is the Serial monitor is still not there then press the reset button again.

If you do it right, You will get a thing in the serial plotter that says:
CAMERA OK
http://69.420.69 or sum other (it varies)

REMEMBER THAT IP!

After that, simply copy paste it to any IDE. Again, READ. THE. FUCKING. CODE.

Then run.

Now you have the feed along with other settings to change the color you guys want to detect. The white screen is where masking is shown. It will show what color you are picking.

Fix it to the color u want. THen run contours and stuff and boom finished. good night <3.
