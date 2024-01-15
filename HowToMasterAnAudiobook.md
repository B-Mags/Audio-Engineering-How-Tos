# How To Master An Audiobook

## Take it step-by-step

The following guide illustrates how to master an audiobook to Recorded Books specifications. All deliverables should meet these specifications. 

If you are new to this process, follow this guide sequentially. 

## 1. Session Details 

### First, check your session details. 
 1. Open the session settings (Setup -> Session).
 2. Set the sample rate is set to 44.1kHz. 
 3. Set the bit depth to 16-bit. 


![Session Setup Image](https://github.com/B-Mags/How-To-Docs/blob/main/assets/SessionSetup.png)

## 2. Importing Your Audio

### Drag-and-drop makes importing easy. 
1. Create a mono track in your Pro Tools session.
2. Drag your audio into the clip bins.  
    a. If your audio does not conform to the session settings, Pro Tools will automatically convert the audio. When this process occurs, the new audio is automatically stored in the session's "Audio" folder. 
3. Drag the audio from the clip bin into your new track. 
4. Tab through the tracks to make sure the chapters are in order on the track.

![New Track Image](https://github.com/B-Mags/How-To-Docs/blob/main/assets/NewTrack.png)

## 3. Check File Durations

### Make sure each file is 60 minutes or fewer. 

If a chapter is longer than 60 minutes, find logical cutting points in the chapter to create multiple files. Each new file must be fewer than 60 minutes. 

<br />

## 4. File Creation

### Create the first file. 

1. Make sure the intro is appended to the first chapter.
   a. There should be three seconds of room tone between the end of the intro and the beginning of the first chapter.

![Create First File](https://github.com/B-Mags/How-To-Docs/blob/main/assets/FirstFile.png)

### Check the gaps and create the rest of the files. 

1. Make sure there are three seconds of room tone at the end of each chapter.
2. Make sure there is a hlf a second of room tone at the beginning of each chapter. 

![Create Chapter Gaps](https://github.com/B-Mags/How-To-Docs/blob/main/assets/ChapterGaps.png)

### Create the last file. 

1. Make sure this file begins with “The End.
2. Make sure the last file contains only the outro credits.
3. Include half a second of room tone at the start of the last file.
4. Include three seconds of room tone at the end of the last file.  

![Create Last File](https://github.com/B-Mags/How-To-Docs/blob/main/assets/LastFile.png)

## 5. RMS and Peak Values

### Check the RMS and Peak values for each file.

1. Open the gain tool in Pro Tools (AudioSuite → Other → Gain).
2. Make sure the “RMS” option is highlighted in the gain too.
3. Select the first file of the audiobook.
4. Click “Analyze” on the gain tool.
 
![Check RMS Value](https://github.com/B-Mags/How-To-Docs/blob/main/assets/RMSvalue.png)  

### Check the peak values for each file 

1. Open the gain tool in Pro Tools (AudioSuite → Other → Gain).
2. Make sure the “Peak” option is highlighted in the gain too.
3. Select the first file of the audiobook.
4. Click “Analyze” on the gain tool. 

![Check Peak Value](https://github.com/B-Mags/How-To-Docs/blob/main/assets/PeakValue.png)  

### If either value falls outside of it specified range: 

1. Use the gain slider to raise or lower the gain.
2. You can see what the result will be in the result window.
3. Click render in the bottom-right corner of the Gain tool to apply the change. 

> Please note: This action will affect both RMS and Peak value. It is possible that in getting the RMS value into the -23dB to -19dB range will raise the peak value above -3dB. Conversely, getting the peak value below -3dB may push the RMS value out of the -23dB to -19dB range. If either case happens, you will need to apply compression to the file.

### If you need to compress the file: 

1. Open the Dyn3 Compressor/Limiter (AudioSuite → Dynamics → Dyn3 Compressor/Limiter)
2. Click “Factory Default” in the top-right corner of the Compressor.
3. Select “Gentle Limiting"
   a. This is a good starting point, and often will get you right where you need to go; however, you may need to tweak the Comp/Limit settings depending on how far off the mark the file is.
4. Use the speaker button, located in at the bottom-right corner of the compressor, to preview the audio.
   a. Remember: Compression degrades audio. Make sure the changes you are making sound good before rendering.
5. Click “Render” to apply the changes.
6. Repeat the RMS and peak value checks.

![Limiting](https://github.com/B-Mags/How-To-Docs/blob/main/assets/Limiting.png)     

### Lather, Rinse, Repeat 

**Remember**: This entire process needs to be done on each individual file. Make sure the RMS and peak values are correct for each file, not the book as a whole. 

## 6. Naming Files 

### Name your files.

Once all of your files are up to spec, it's time to name your finalized files. You can do this easily using the Auto Rename tool in Pro Tools. In the example, we are working on the book The Secret Life of Lilian Velvet by Jaclyn Moriarty.

Our naming convention is as follows: All files must be named 001_TitleOfBookAUT, 002_TitleOfBookAUT, etc., where AUT is the first three letters of the author's last name. The sample file should be named TitleOfBookAUT_Sample. 

**Please Note**: If the title of the book begins with an article, you must omit that article when naming files. For example, files for The Secret Life of Lilian Velvet by Jaclyn Moriarty would be named: 001_SecretLifeOfLilianVelvetMOR, 002_SecretLifeOfLilianVelvetMOR, etc. The sample would be named: SecretLifeOfLilianVelvetMOR_Sample. 

If any file in the audiobook fails to conform to this naming convention, the title is automatically kicked out of production, often leading to delays in publication. 

### A quick method for naming your files  

**Please Note**: To use this method, your files must be named sequentially before using the Auto Rename tool, otherwise your files will be named out of order. Always double check that your files were named correctly after using the Auto Rename tool. 

1. Open the Auto Rename Tool.
    <br />a. Select all files in the track.
    <br />b. Click the down arrow in the top right corner of the Clips Bin.
    <br />c. Select “Auto Rename.”
2. Set the naming parameters.
3. Click OK.
4. Select all files.
5. To commit the name change to the disk, use the Rename tool.
    <br />a. Select all files in the track.
    <br />b. Click the down arrow in the top-right corner of the Clips Bin.
    <br />c. Select “Rename.”
6. In the dialog that pops up, ensure that “name clip and disk file” is selected.
7. Click OK for each file.
8. Finally, name your sample file TitleOfBookAUT_Sample.
    <br /> a. In our example, the sample would be named SecretLifeOfLilianVelvetMOR_Sample.



