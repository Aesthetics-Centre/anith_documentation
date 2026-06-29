# Image stacking 

Siril is an astronomical image processing tool. 
It is specially tailored for noise reduction and improving the signal/noise ratio of an image from multiple captures, as required in astronomy.

![Description](https://drive.google.com/thumbnail?id=1vLYsT1vTV92vH9ip0NfFCjL5kiDjnh3y&sz=w800)


## Software needed:
 
- [Siril](https://siril.org/download/) 
- [Starnet](https://starnetastro.com/)

## Siril Download

Download the software needed and first we will start with downloading the Siril Software from the above link and download based on the operating system you are running.

![Description](https://drive.google.com/thumbnail?id=1xnaaIhzRvNPh9dQushljE9oRYGeEnv3o&sz=w800)


once you are done with downloading the software then drag the Siril app to the application folder and then the Siril software will be installed as shown below.

![Description](https://drive.google.com/thumbnail?id=18duH4R2LypopATMvWkK5hqzu1I7aTfit&sz=w800)


## Siril

### Siril Interface

then after the installation, you can open the application and then you will see something like this.

### Starnet download

after you are done with the downloading of the siril software then the next software that we will need is starnet and this software will help us to change remove the stars from the image so that we can get the image with the stars as shown below.

![](https://www.cloudynights.com/uploads/monthly_02_2022/post-335242-0-55678300-1645352206.jpg)

we will use this tool later in the workflow.

![Description](https://drive.google.com/thumbnail?id=1w_i5B-m0WyJWz84_mUZvXFLgjvLcjjkJ&sz=w800)


### What is image stacking

Image stacking is the process of taking multiple, shorter exposures of the night sky and blending them into a single, master photograph using specialized software. It artificially simulates a very long exposure to reveal faint deep-sky details while dramatically reducing digital noise.

Stacking multiple exposures reduces noise, prevents star trailing, and pulls out faint nebulae details.
- Light Frames: Your primary photos containing the actual night sky.
- Dark Frames: Photos taken with the lens cap on at the same temperature and exposure time to record sensor thermal noise.
- Flat Frames: Photos taken of a uniformly lit white surface (e.g., a lightbox) to cancel out lens vignetting and dust specs.
- Bias/Offset Frames: The shortest possible exposures with the lens cap on, used to read the baseline electronic noise of your camera's sensor.

### Stacking the light Frames on Siril

so when we open the siril software and the interface will look like this:

![Description](https://drive.google.com/thumbnail?id=11UOXeK8inxTNXdfLoGGgaBOCCcuZot3P&sz=w800)


to more about the main interface, you can view the documentation here to understand the terminologies. [Here](https://siril.readthedocs.io/en/stable/GUI/main-interface.html)

### Stacking Only light frames.

we will be following this tutorial to do our first stacking and use these image data taken by by Panoptes Unit at the Academy [Image resource](https://drive.google.com/drive/folders/1K3tto_GeGD75UMn4doWtC3OKYE3jnyh4?usp=sharing)

you tube video: https://www.youtube.com/watch?v=EvMZox2dlZA 

### Prepare the files.

With this process we will be able to run a prebuilt script and and stack the light frames to quickly see how things are looking..

After downloading the fits file from the image resource, you will have multiple images of an object therefore with more images we can amplify the data by stacking.

One important thing about this process is to know the default scripts available.

![Description](https://drive.google.com/thumbnail?id=1uiVR174vwAULyidl4S-CCzwPkb0sBHzs&sz=w800)


![Description](https://drive.google.com/thumbnail?id=1xRiYKaLjLOrCT_ZJAH_XRgnPhsIR0ZlG&sz=w800)


in the above image you can see "Get Scripts", here you can add script from the available scripts as shown below and select "Mono_Preprocessing_WithoutDBF" from the available list.

![Description](https://drive.google.com/thumbnail?id=1vTS_6oC7UaoePZ9trfbZmvYQgExPZFfd&sz=w800)


and therefore we can stack the images without the calibration frame (Dark, Flat and Bias Frames).


- if you are unable to find the script then refer to the youtube video and download the script from 2:23 of the video [link to script](https://free-astro.org/index.php?title=Siril:scripts)

now put all the downloaded fits file inside folder name "Lights"

### Import and Stack the files.

now on the top bar, you can see a home icon, click the home icon and navigate to the folder where your Lights folder is present and click open.

![Description](https://drive.google.com/thumbnail?id=1U4O0LRxuB8pwdxG3XkurWFjjgVx0AwJK&sz=w800)


After that is done then you can click on the script tab and clicl on the script "Mono_Preprocessing_WithoutDBF". Then click Run Script.

![Description](https://drive.google.com/thumbnail?id=1i4F_M-RLV8LP2z5SsEcpr7xoXQ-e3HcT&sz=w800)

After the script is completed then you can see something like this, the time taken will depend on number of images you will stack.

![Description](https://drive.google.com/thumbnail?id=1leR1GcCWoet20T1UTX0UeHs4N9Yb5_VV&sz=w800)


### Processing.

Once you complete the script excuation now in the folder where light folder was present, you can now see a folder name "process" and a file name "result.fit".

![Description](https://drive.google.com/thumbnail?id=1AjPFB_ITXcEJztqlr9i-ZPvAxGGvyvA7&sz=w800)


- Therefore stacking large amount of image will consume more space as it creats multiple files.

Now once this process is done, you can click on open tab at the top left corner of the interface and open the results.fit file.

![Description](https://drive.google.com/thumbnail?id=1n3Qdj4qB_42lSK_E9RoC8z-wLqD_P9Xy&sz=w800)


at the botton of the image, make sure display mode is "Auto Stretch" so that you can see more detail.

![Description](https://drive.google.com/thumbnail?id=1leR1GcCWoet20T1UTX0UeHs4N9Yb5_VV&sz=w800)


after this, you can work on different aspect to amplify the details as per your requirment.

## StarNet

### Removing the stars.

Now as you have notices the details of the stars has also been amplify and for this purpose we will use this tool called "StarNet"

you can download the StarNet tool from this [Lin](https://starnetastro.com/cli-tools/starnet/) and download based on your operating system.

after this you can install the package.

![Description](https://drive.google.com/thumbnail?id=13wha8IMAyMzdQZ7JEWNFi7Eo9jNezuEa&sz=w800)


![Description](https://drive.google.com/thumbnail?id=1DTNC7P4VBo5RPFtTcxuAIBb0Oz24b-Mp&sz=w800)


or you can download the zip so that we can directly link the file to siril.

Then you can navigate to preference and the click on "miscellaneous" and click on the label below and naviagte inside the folder extracted from the zip file downloaded

![Description](https://drive.google.com/thumbnail?id=1E5_74w35NwztPlbb2pxqe7zZNvb0RbOs&sz=w800)


- might be usefule if you find error: [Link](https://www.youtube.com/watch?v=5OjjX81q1Ck)

and to know more about star net ++ :

- youtube video link : https://www.youtube.com/watch?v=Y-WmMvepTHA&t=852s

and once the process is complete you can see that the stars are removed

![Description](https://drive.google.com/thumbnail?id=1Rw7YoYY_qtBx8B8b3bR9l8o0s-AsaAlS&sz=w800)


and then once you are done you can export the image in png or fits as per your requirment. and this is the output of exporting a png file.

![Description](https://drive.google.com/thumbnail?id=1vckkKiw4VYqrtBy6Klcx49GVrRNAu06G&sz=w800)








