#  Studio User Guide 

### About This Guide

If you are setting up the studio for the first time, or if you need step-by-step guidance, work your way sequentially through the dropdown steps below. 

If you don't need a walkthrough, feel free to skip ahead to “Hardware Quick Settings (Reference Sheet)." There you will find all of the settings without the walkthrough. 

# Table of Contents 

[1. Hardware Setup](https://github.com/B-Mags/Audio-Engineering-How-Tos/blob/main/RecordingStudioUserGuide.md#1-hardware-setup) <br>
[2. Big Knob Settings](https://github.com/B-Mags/Audio-Engineering-How-Tos/blob/main/RecordingStudioUserGuide.md#2-big-knob-settings) <br>
[3. Pro Tools Walkthrough](https://github.com/B-Mags/Audio-Engineering-How-Tos/blob/main/RecordingStudioUserGuide.md#3-pro-tools-walkthrough) <br>
[4. Hardware Quick Settings](https://github.com/B-Mags/Audio-Engineering-How-Tos/blob/main/RecordingStudioUserGuide.md#4-hardware-quick-settings) <br>

## 1. Hardware Setup 

> _**Note Before Starting**: Follow the steps sequentially. It may be beneficial to check your settings and hookups against the Quick Settings Guide and the Owner's Manual Hookup Diagrams._

### Input/Output Connections 

1. Computer Connection <br> 
   a. Connect the computer to the USB port located on the back panel of the Big Knob. 
2. Monitor Connection <br>
   a. Plug the left monitor into the Monitor A (L) slot. <br>
   b. Plug the right monitor into the Monitor B (R) slot. 
3. Microphone Connection <br> 
   a. **IMPORTANT**: Disengage phantom power on the Big Knob and the Drawmer before connecting condenser microphones. Failing to do so may result in a pop that could damage the microphone. <br> 
   b. Connect the microphone to the Drawner's Mic Input. <br> 
   c. Connect the Drawmer's output to Microphone 1 on the Big Knob. 
4. Optional External Stereo Connection <br>
   a. Connect external source, such as an iPhone or iPad, to the Stereo ¾ 3.5mm jack located on the front panel of the Big Knob. 

## 2. Big Knob Settings

> _**Note Before Starting**: To monitor changes, raise the Big Knob's big knob a quarter turn._ <br>  

### Settings

#### 1. Onyx Mic Preamps

1. Depress the +48V button to engage the Big Knob's phantom power.
2. Depress the ½ button to allow audio from microphone to come through studio monitors.
    - This button should be illuminated green at all times. 
3. Disengage Stereo Pan to ensure recorded audio is recorded to both left and right channels.
4. Raise the 1(L) knob to a suitable playback volume.
5. Move to the back plate of the Big Knob and locate the REC SRC SELECT button in the USB section. This button should be depressed, which will select the ½ input as the recording source within the computer's DAW. <br>


#### 2. Playback From Computer Input 

1. Depress the USB button to allow audio from the computer to come through the studio monitors.
   - This button should be illuminated green at all times.

#### 3. Studio Monitors

1. Depress both A and B buttons in the Monitor Select section of the board.
   - The gain for each monitor is controlled by its corresponding TRIM knob located above the A and B buttons.
2. Depress the Mono button located just below the Big Knob.
   - This button should be illuminated green at all times. <br>
3. To mute the studio monitors, depress the Cut button located just below the big knob.
4. **Optional**: To drop the sound coming through the monitors by 20dB, depress the DIM button located just below the big knob. For our purposes, this can typically remain off. <br> 

#### 4. Headphone Monitoring

1. Depress the 2TR/CUE Button located just above the Phones 1 and Phones 2 knobs.
   - This will allow you to monitor all signals, including the talkback microphone.
2. Blend the input and playback signals by turning the Direct Monitoring knob.
   - **IMPORTANT NOTE**: Confusingly, the Direct Monitoring knob does not affect the talkback level despite both having the same “cue” label. Please use the Talkback Volume knob to adjust the volume of the talkback button, and, as mentioned above, ensure that the 2TR/CUE button is depressed to enable the talkback mic.

## 3. Pro Tools Walkthrough

1. Set the playback engine
   - Navigate to Setup > Playback Engine.
   - In the window that opens, open the dropdown menu next to Playback Engine, and select BIG KNOB.
2. Set the I/O
   - Navigate to Setup > I/O.
   - Navigate to the output tab.
   - Select and delete all current output paths.
   - Click the default button to create a new output path.
   - Repeat these steps in the input tab.
3. Create a New Session
4. Create a New Track
   - For the track’s input, select Analog 1 (mono).
   - For the track’s output, select Output 1-2 —> Analog 1-2.
  
## 4. Hardware Quick Settings 

### Onyx Mic Preamps 
| Setting Name | Set To |
|---|---|
| +48 Button  | Always Released |
| Stereo Pan Button | Always Released |
| 1/2 Input | Always Depressed | 
| 1(L) Knob | Turned to a suitable level |

### 2-Track Source Select 
| Setting Name | Set To |
|---|---|
| 2(R) Knob (if using second mic) | Turned to a suitable level |
| 3/4 Button | Depressed if using external source | 
| 3/4 Trim Knob | Turned to a suitable level | 
| USB Button | Always Depressed | 

### Monitor Select
| Setting Name | Set To |
|---|---|
| A Button | Always Depressed | 
| B Button | Always Depressed | 
| A Trim Knob | Turned to a suitable level | 
| B Trim Knob | Turned to a suitable level | 

### Big Knob Selection
| Setting Name | Set To |
|---|---|
| Mono | Always Depressed | 
| Mute | Depress if muting monitors | 

### Headphone Monitoring
| Setting Name | Set To |
|---|---|
| Direct Monitoring Knob | Blend input and playback signals to taste--knob will likely be mid-range. | 
| Phones 1 Knob | Turned to suitable level | 
| Phones 2 Knob | Turned to suitable level |
| 2TR/CUE Button | Always Depressed |

### USB (Back Panel)
| Setting Name | Set To |
|---|---|
| REC SRC SELECT | Always Depressed |
