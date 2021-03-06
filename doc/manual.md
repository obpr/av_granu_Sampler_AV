# AV_GRANU

Double tracks AV sampler
In real time, Sample, Scratch, Pitch and change the playback speed
and module your parameters with 2 complex step-sequencers and an audio analyzer.

![Alt text](/doc/img/avgra_tout.jpeg)


Play music with video samples.
Realize live montages and generative installations.
Choose sounds and vidéos and find interactions among them:
- Two audio/video tracks (right:A left:B)
- (1) Sound analyse modules
- (2) Time stresh modules
- (3) Step Sequencers
- (4) Synthetizers
- (10) Speed and Pitch playback


(https://obpr.balik.network)


- [AV_GRANU](#av_granu)  

  - [Step sequencers](#step-sequencers)
    - [`[=IT]`](#it)
    - [`[≠IT]`](#it-1)
    - [`[%T]`](#t)
    - [`[/Tb/]`](#tb)
    - [`[A]`](#a)
    - [`[nxt]`](#next)
    - [`[ø]`](#)
    - [`[⇋]`](#-1)
    - [`[⇗]`](#-2)
    - [`[O]`](#o)
  - [Selectors and modulations](#selectors-and-modulations)
    - [Gate](#gate)
    - [`[raw]`](#raw)
    - [`[@]`](#a-1)
    - [`[⤷@]`](#⤷@)
    - [`[@]`] orange on black(#-3)
    - [`[⇪]`](#⇪)
    - [ `[◐]` and `[•]`](#-◐-and-•)
    - [`[◐]`](#◐)
    - [`[•]`](#•)
    - [`[๏]`](#-4)
    - [`[ø]`](#-5)
  - [Audio modulations](#audio-modulations)
    - [Left’s 2 columns:](#lefts-2-columns)
      - [Select data source](#select-data-source)
        - [`[bck]`](#bck)
        - [[O]](#o-1)
        - [slider](#slider)
      - [Choose data source](#choose-data-source)
        - [`[A]`, `[B]`, `[a']` or `[b']`](#a-b-a-or-b)
    - [Right’s 2 columns](#rights-2-columns)
      - [Module data from the left ’s 2 columns](#module-data-from-the-left-s-2-columns)
        - [`[44]`](#44)
        - [`[O]`](#o-2)
      - [Choose data source](#choose-data-source-1)
        - [`[A]`, `[B]`, `[a]` or `[b']`](#a-b-a-or-b-1)  
     - [Time stretching unti'l drone](#time-stretching-until-drone)
  - [Audio analysis](#audio-analysis)  
    - [Select a source](#select-a-source)
      - [`[A]`](#a-2)
      - [`[C]`](#c)
      - [`Mode scratch` / `[sctch]`](#mode-scratch--sctch)
      - [Sensibility](#sensibility)
      - [Progressivity](#progressivity)
      - [[stp]](#stp)  
  - [Files selection](#files-selection)
  - [Video settings](#video-settings)
  
  

## Step sequencers
(3)  

![Alt text](/doc/img/avgra_step.jpeg)  


Two Step sequencers called A and B generating number sequence according to:

- (5) A number sequence of time
- (6) A number sequence of iteration
- (7) A number sequence of progressivity
- (8) A number sequence to be added or subtract

Apply the datas to:

- (9) The position of the loop
- (10) The Pitch and the speed simultaneously
- (11) The speed only
- (12) To the pitch only
- (13) Synthetizers

*`$` = value, each step got a value*

### `[=IT]`
- Play all `$` of time (all `$` of Step sequencerT)
at each value of the general Step Sequencer (top line) ... allT `$ / G $`
- If it is not triggered = Play a `$` of the Step sequencerT at every `$` of the general sequencer Step ... `T $ / G $`

### `[≠IT]`
- Change steps on the step sequencer (s) in accordance with a fixed $ of time (1000) by default).
- Column still on the right: go to the value gradually (1000) by default)

### `[%T]`
- Divides time by the `$` from Step Sequencer `IT` ... `T` `$% IT`

### `[/Tb/]`
Receive the time of Step sequencer B

### `[A]`
On/off

### `[nxt]`
Step forward

### `[ø]`
Reverse steps off and steps on

### `[⇋]`
Send a step on two opposite values

### `[⇗]`
Move linearly on the sequence.
- One step all 6.25`$` (100%16 = 6.25)
- if the tempo = loop length of the sequence%10

### `[O]`
Turn this step mute


## Selectors and modulations


Choose position(s) to the starting point of the loop:

- Add value to this position(s)
- Move the position(s) along the whole sequence
- Apply enveloppe to sound track and opacity to video layer


### Gate
(14)   

 
![Alt text](/doc/img/avgra_gate.jpeg)


Set the position of the playhead where to start the playback loop

### `[raw]`
Raw data  A or B

### `[@]`
Make a loop on the fly and change position with Step sequencers

### `[⤷@]`
Call back the loop made in `[@]`. When released, read what is after the loop chronologically or with the `[@]` orange on black mode go back where you were at your last `[⤷@]`

### `[>๏]`
Press on, press off (silence) (*midi mod*)

### `[⇪]`
Lock selected source (*midi mod*)

If you choose to send files triggered by A or B or randomly with `[BB](A)` or `[_BB1](B)` the sample sent will be played at its beginning

###  `[◐]` and `[•]`
Auto-receive On/off step and send enveloppe to
the sound selected.

### `[◐]`
On/off step

### `[•]`
Send enveloppe to the sound selected (16)

### `[๏]`
Send on/off step and set enveloppe from sources selected in
s&p, speed, or pitch


## Audio modulations  
 Control both Speed and Pitch or separately. 
![Alt text](/doc/img/avgra_audiomods.jpeg)

- (10) ω&♪-Speed and pitch 50 = 0= stop, 75= go forward , 25= go back
- (11) ω-Speed only 50 = 0= stop, 75= go forward , 25= go back
- (12) ♪-Pitch only 0 = default

### Left’s 2 columns:

#### Select data source

##### `[bck]`
Back to default `$` after selection released

##### [O]
Go back to default `$`

##### slider
set value

#### Choose data source

##### `[A]`, `[B]`, `[a']` or `[b']`

### Right’s 2 columns

#### Module data from the left ’s 2 columns

##### `[44]`

Choose between `44100`/`88200` hz

##### `[O]`

- Go back to default `$`
- Slider: set  modulation value

#### Choose data source
##### `[A]`, `[B]`, `[a']` or `[b']`


## Time stretch  `[☞]`

(2)  

![Alt text](/doc/img/avgra_timestretch.jpeg) 
Advance your number sequence, pattern, over the entire sample.

Make the pattern you are making with Stepseq `A` or `B` sliding along the loop lenght more a less rapidly:

- Select entry point in the sample
- Select exit point
- Select stretching value

## Audio analysis  

(1)  

![Alt text](/doc/img/avgra_audioanlalyse.jpeg)

Analyze silences and attacks in the audio signal of sampler or synthesizer. Send the values as `[a']` or `[b']`

### Select a source
#### `[A]`
Track AV left

#### `[C]`
Upper synthetiser in purewave-synth

#### `Mode scratch` / `[sctch]`
Suite de valeurs opposées `0-100`, `25-75`, etc.

#### Sensibility

#### Progressivity

#### [stp]
- Mode steps: numbers of sequence
- number of step$ 1 to 5


## Files selection  

(14)  

![Alt text](/doc/img/avgra_fileselection.jpeg)  

Select audio and vidéo loop. Call bank or single audio and video files:

- Data bank video
- Data bank AV
- Data bank audio
- Link A&V selection

- Select the file number..
- Open browser
- Select the file with `A` or `B`
- One random selection
- One random selection
under the speed of Step sequencer `[BB](A)` or `[ BB1](B)`
- clear Drop down menu
- Open browser
- Drop down menu


## Video settings  

(15)  

![Alt text](/doc/img/avgra_videospecs.jpeg)  


Set video specifications. Dimension, frame rate, incrustations and image modulations

- Threshold: Turn pixel transparent according to the color
- Change height and width
- Change only width
- Change only height
- Change ratio height/width
- Get dimension of the video sample
- Change XYZ
- Contrast
- Saturation
- Motion blur
- On/off
- Receive On/off
- Invert color
- Audio control opacity


## Synthetizers  
(4)  

![Alt text](/doc/img/avgra_synths.jpeg)  

## Equalizer, dynamic enveloppe and reverb 

![Alt text](/doc/img/avgra_EQ_ENV_Reverb.jpeg)

## Pure data specs:
- Pd 0.48.0  
- Download and instal library from obpr/av_granu_Sampler_AV/scr/avgrau_libs.zip 

## output video

![Alt text](/doc/img/avgra_outputvideo.jpeg) 
=======

# video specs:  
- H.264, P frame every frame ( done with quicktime player 7 for exemple)

# audio specs:  
- .wav, lenght under 30 seconds at 88200 Hz 1 minute at 44100 Hz  
- Change from  88200 Hz to 44100 Hz with the [44] button in Pitch and speed module(10)
