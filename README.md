# Voice-Recorder-for-Voiceprint-Testing

Docker: 2.1.0.0(36874)

## Docker Installing

https://www.docker.com/products/docker-desktop

## Run the Voice Recorder Website

Use Terminal (or cmd on Windows) and cd to the root path of this folder.

Run

        docker-compose up

Then use Chrome to browse https://0.0.0.0:8443.

The code of the webpage is in the "website" folder.

## Voice Recorder Procedure

* Page Index: 

    Key in Username and Get Consent on Collecting Data.
    
    Before the recording, please make sure that the participant agrees for the data collection and development.

* Page Fixed Letter 1,2,3,4 & Random Speech 1,2: 

    Press "Start" to start recording and "Stop" to stop recording.
    
    After recording, press "Download" button to save .wav files to "Data" folder.

## Voice Recording Summary

In the "py" folder, there are some python code to extract information from .wav filenames into an excel.

For data security, the method to change username into anoumous ID is also provided.




