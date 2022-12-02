# Visual Field Test Experiment (2022)

In this work, we designed a series of experiments to discover if performing visual field tests via brain-computer interface (BCI) is feasible. As ophthalmologists used a series of visual field maps to detect the changes in visual field defects for glaucoma patients, measuring the rate of disease change. Our work focuses on functional examination by effectively extracting visual field defects through the use of BCI. This will give ophthalmologists insight into diagnosing ocular disease and detecting glaucoma progression. Similar to the scenario of visual field assessment by standard automated perimetry (SAP), the subjects are looking at the centre of the screen while flickering light is displayed across the screen at different angles. 

However, instead of responding by clicking a button when one stimulus is presented, our goal is to detect the visual stimuli presented on the screen by extracting the responses from EEG. Doing so serves as an objective measure of visual fields that allows for the monitoring of the electrical brain activity associated with visual field stimulation, requiring no motor response from the participants and relatively uninfluenced by "higher" cognitive activity. As such, patients do not need to learn how to use the system and do not have to click the button at the right time. In our experiments, we presented stimuli within the central vision, the inner 30 degrees of vision. We investigate this portion of space as it is an essential part of a person's vision, and beneficial for performing daily tasks and recognizing persons and objects.

# Experiment Protocol

[![Visual Field Test Experiment Video](https://img.youtube.com/vi/frE9CwnvVwM/0.jpg)](https://www.youtube.com/watch?v=frE9CwnvVwM)

## 3 sessions

1) **binocular** - both participant's eyes were tested 
2) **right monocular** - the participant's left eye was blocked, and the right eye was tested
3) **left monocular** - the participant's right eye was blocked, and the left eye was tested

## For each session

There were ten blocks in each session. Participants would rest between two consecutive blocks. Each block to containing 20 trials.

## For every trial

One stimulus will be presented on the screen. Each trial started with a 1-second cue with a short beep and a central white fixation shown on the screen. After the cue, the visual stimulation lasted for 4 seconds. Then, the screen will be blank for 1 second before the subsequent trial begins automatically. The total trial duration is 6 seconds. During the visual stimulation, the participants fixed their gaze toward a central fixation point on the screen.

## Numbers

- **Number of channels**: 64 channels
- **Sampling frequency**: 1000 Hz
- **Number of participants**: 63
- **Number of sessions**: 3
- **Number of blocks per session**: 10
- **Number of trial per block**: 20
- **Number of targets**: 20
- **Duration per trial**: 6 seconds
- **Duration of stimulation**: 4 seconds
