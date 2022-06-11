# Android LaunchPad application
A android launch pad application for Gachon University 2022 1st semester Mobile Programming 

### Brief Description

* #### 4 Types of instruments: users can play 4 instruments in the app, easy to switch from one another
* #### 12 pad buttons: using 12 buttons in the app, users can easily play music
* #### 8 loop stations: maximum 8 loops can be used, users can play 8 roles at the same time

  * input parameter : org_df
   * org_df (type: DataFrame) >> Target of LabelEncoding
  * output : Return DataFrame after LabelEncoding


### Contents
* #### Metronome 
  * Metronome is used for setting and playing tempo
  * Helps you play notes on the right beat. Also used to specify the beat and tempo of the music to be recorded when using a loop station
  * Pressing the metronome button allows you to set three time ticks and additional tempo
  * In the case of tempo, the types of tempo used musically are listed and ordered
  * Can change value while running metronome

* #### Instrument
  * Consists of piano, drum, bass, and guitar
  * Selectable instruments using ScrollView in the upper left corner
  * For piano and the bass, the note of each button is mapped, so you can play it in various ways
  * For pianos, the octave can be changed using the octave change button at the bottom, as the range used varies (octave from 1 to 5)
  * For drums, 12 basic sounds are mapped
  * For guitar, if you map each note, it is difficult to make an overall sound, so you have to map the sound by strum method, which is a method of making harmony while sweeping down the guitar string with your hands. So you can make rich sounds with just single button


* #### Pad
  * There are 12 pads in total.
  * On the pad, icons are set for each instrument to intuitively understand the buttons. Therefore, if you change the instrument in the instrument category, the icons and sounds change accordingly
  * A sound when you press a note quickly multiple times doesn't interfere other sounds
  * Supports simultaneous input for all instruments, prevents interruption of other sounds


* #### Loop station
  * A loop station is a function of repeatedly playing recorded sounds, which allows other sounds to be stacked on the recorded section
  * It consists of eight buttons, each button can have one loop. So you can create a total of 8 loops
  * When you press the first button, you play a beat according to the beat and tempo specified by the metronome, and the recording begins
  * The REC mark appears and recording proceeds, and the recording length is four times that of the designated beat table, so that four bars are recorded. For example, if it's 4/4 beats, the recording is done for a time that can hold 16 quarter notes
  * The center button shows the progress of the current beat so that you can record it continuously
  * After recording, it changes to "READY". In the READY state, the button can be pressed once again to play. Play looped music until you press it again to stop
  * Press and hold the READY button for more than 1 second to clear the saved sound. Function for re-recording when recorded notes are incorrect or played incorrectly
  * All independently operated by button. The other button is disabled when another button is recording. It is possible to play in batches and stop in batches through the button located in the center of the top.
  * Can be played using a pad even when the roof station is operating


### Implementation Details




### How to use




