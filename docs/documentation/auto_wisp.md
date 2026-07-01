## Autowisp

[AutoWISP](http://arxiv.org/abs/2507.15830), for extracting high-precision photometry from citizen scientists' observations made with consumer-grade color digital cameras (digital single-lens reflex, or DSLR, cameras), based on our previously developed tool, AstroWISP.

![Description](https://drive.google.com/thumbnail?id=1BhvJVS9HMZIB7ECbB4y-IOgH7cQfxbeU&sz=w800)


> pip3 install autowisp

this command will download and install the autowisp to your computer.

> wisp-bui

this command will open the GUI on a browser similar to the image below.

![Description](https://drive.google.com/thumbnail?id=175y3Vov1eFmTIiqI3WAhXwDzsoeWb7gE&sz=w800)


and if the GUI is not coming up the you can try this commadn

> python3 -m autowisp.browser_interface.start

1. to start create a new project.

![Description](https://drive.google.com/thumbnail?id=1aFqybbNVWGuLzrZCUiftrPkbPZcfMi13&sz=w800)

2. once you create a new project then you need to add some of the details such as 

![Description](https://drive.google.com/thumbnail?id=1BhvJVS9HMZIB7ECbB4y-IOgH7cQfxbeU&sz=w800)

and for this task we can set a project name (name of the project) and project home (folder where you want to save the project file during the process)

the image below shows the interface when you click on the project home field

![Description](https://drive.google.com/thumbnail?id=1BhvJVS9HMZIB7ECbB4y-IOgH7cQfxbeU&sz=w800)


3. In our context we will not be using the calibration frame such as bias, dark and flat file. therefore make sure the frames are turnned off as shown below.

![Description](https://drive.google.com/thumbnail?id=1hm4gDuyGMPcEX9aTlWr4XuPNAJwo1dq1&sz=w800)




## errors I got:

after the autowisp started to the process but then i found an error at the astrometry step.

![Description](https://drive.google.com/thumbnail?id=1cRf8eQ4m9AVCuysAPKr5RL7JtjppY0kR&sz=w800)

and when the error was expanded it showed this detail.

![Description](https://drive.google.com/thumbnail?id=1eqHRIZYGbvZIFJvgrmuWfB_oOEZFXbkK&sz=w800)



- calibrate: basically looking at the files - form the header (RA. DEC and )
- fins star: locating the star
- solve astrometry : finds the images and name it using astrometic.net
- fit star shape: it does the statictic so that images pixel