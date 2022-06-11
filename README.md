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
* #### Metronome: Metronome setting and tempo setting button
  * Helps you play notes on the right beat. Also used to specify the beat and tempo of the music to be recorded when using a loop station
  * Pressing the metronome button allows you to set three time ticks and additional tempo
  * In the case of tempo, the types of tempo used musically are listed and ordered
  * Can change value while running metronome

* #### Instrument
  * Consists of piano, drum, bass, and guitar
  * Selectable instruments using ScrollView in the upper left corner
  * In the case of the piano and the bass, the note of each button is mapped, so you can play it in various ways
  * In the case of drums, 12 basic sounds are mapped
  * In the case of guitar, if you map each note, it is difficult to make an overall chord sound, so you have to map the sound by strum method, which is a method of making harmony while sweeping down the guitar string with your hands. So you can make rich sounds with just one button
* For pianos, the octave can be changed using the octave change button at the bottom, as the range used varies (octave is supported from 1 to 5 as is typical piano)

* #### Pad
  * input parameter : org_df
   * org_df (type: DataFrame) >> Target of LabelEncoding
  * output : Return DataFrame after LabelEncoding


* #### Loop station
  * input parameter : org_df
   * org_df (type: DataFrame) >> Target of LabelEncoding
  * output : Return DataFrame after LabelEncoding


### Implementation Details




### How to use




