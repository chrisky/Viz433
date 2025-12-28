## Introduction
Viz433 is a simple visualiser for timed data, e.g. a series of numbers that represent pulse time spans.  

The initial purpose was to visualise caputures from the [RFXcom](http://rfxcom.com/) 433 MHz to USB transciever, although this project is in no way affilliated with RFXcom.  I do like their procucts, though.

Viz433 a single HtML page, relying on the Paper.js framework for some of the graphics.

This is ble to show time series captured from that device, as presented in the logs of the RFXmngr.exe application.  

Since 433 MHz pulse data typically repeats, it can be a little challenging to identify which numbers are for pilot sequences, which numbers are for the payload, and the inter-block pauses.  Viz433 can help a lot.

## Usage

View the web page in a recent browser. E.g. click [here]()
<img width="1130" height="1132" alt="image" src="https://github.com/user-attachments/assets/f08d26f3-7929-4d02-bc25-df35602e23bf" />

Paste in some numbers from the log captured by the rfxcomm unit, as seen in RFXmngr.exe.
<img width="983" height="539" alt="image" src="https://github.com/user-attachments/assets/bd6c7b70-573b-4365-8b14-4625d7550f93" />

Paste them twice.  
<img width="2268" height="941" alt="image" src="https://github.com/user-attachments/assets/f4e4b613-b346-45e9-ba65-8b80e5e6c44c" />

Drag the bars and zoom and identify the corellations.

You can now identify the numbers that form the pilot sequences and payload.

Once you've identified and edited the numbers, enter them in their own timeline and see if this is a good match:
<img width="1677" height="283" alt="image" src="https://github.com/user-attachments/assets/f63a8372-ba05-4ec7-a5c9-73975fe49c13" />

If all goes well, you now have a sequence that can be included per the instructions on the RFXcom help site for use e.g. in Home Assistant.  See the RFXcom downloads page [HERE](http://rfxcom.com/downloads.htm), and the info is in Chapter 18  *Receive and Transmit RAW data*.

Good luck!


