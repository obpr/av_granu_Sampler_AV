# AV_GRANU

Double tracks AV sampler


![Alt text](/doc/img/avgra_tout.jpeg)


Play music with video samples.
Realize live montages and generative installations.
Choose sounds and vidéos and find interactions among them.

Two audio/video tracks (right:A left:B)
Two Sound analyse modules (up:a' down:b')
Two Synthetizers (up:C down:D)
 

Very versatile object for playing sound and video clip simultaniusmly, av_granu allow you to specify the starting point of a repeating loop within the sample. The playback speed (either forward or backward) and also the playback speed separtly from the pitch.

Compose in two complex step sequencer and apply the results on the playhead scrolling through audio sample or to the synthesizers. Analyse the results and send back the traduction to module the sounds between each others.




#Dynamic enveloppe

According to the speed of the source selected, draw envelopes from regular one to granular.


Left/up column : raw data 
Right/down column : mod raw data



#Looping 

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

### `[∞]`
Lock selected source (*midi mod*)


### `[◐]`
On/off step ( Trigger )

###  `[◐]` and `[•]`
Auto-receive On/off step ( Trigger ) and send enveloppe to
the sound selected.

### `[•]` left side of the slider « mod » 
Send enveloppe from A, B

### `[•]` right side of the slider « mod » 
Send enveloppe from a’, b’, C or D


###  green `[ø@S]` If you choose to select files with A or B CVs or randomly with A or`B triggers the sample sent will be played at its beginning

###  green `[•]` If you choose to select files with A or B CVs or randomly with A or`B triggers the enveloppe will be triggered.


## Time stretch  `[☞]`

![Alt text](/doc/img/avgra_timestretch.jpeg) 
Advance your number sequence, pattern, over the entire sample.

Make the pattern you are making with Stepseq `A` or `B` sliding along the loop lenght more a less rapidly:

- Select stretching value
- choose the sensibility of your knob


#Audiomods  — ω&♪ —  ω —  ♪ —

 Control both Speed (ω) and Pitch (♪) or separately. 

![Alt text](/doc/img/avgra_audiomods.jpeg)

 ω&♪-Speed and pitch 50 = 0= stop, 75= go forward , 25= go back
 ω-Speed only 50 = 0= stop, 75= go forward , 25= go back
 ♪-Pitch only 0 = default

Left/up column : raw data
Right/down column : mod raw data

##### `[bck]`
Back to default `$` after selection released

##### [O]
Go back to default `$`

##### slider
set value

##### `[44]`

Choose between `44100`/`88200` hz

##### `[O]`

- Go back to default `$`
- Slider: set  modulation value

#### Choose data source
##### `[A]`, `[B]`, `[a']` or `[b']`


## Synthetizers: C and D
(4)  

![Alt text](/doc/img/avgra_synths.jpeg)  


Send D thought C

##Attack interpret

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

#### Gate

#### Progressivity

#### [stp]
- 
- Mode steps: numbers of sequence
- number of step$ 



## Video settings  

![Alt text](/doc/img/avgra_videospecs.jpeg)  

Apply trigger, cv ,gate and enveloppe to the video opacity accordingly to audio:

ø on off video layer
◐ receive trigger 
•   receive enveloppe audio 
AV receive gain 
/2 receive half the gain 

Set video specifications. Dimension, frame rate, incrustations ( high-threshold_) and image modulations

- Threshold: Turn pixel transparent according to the color
- Change ratio height/width
- Change XYZ
- Contrast
- Saturation
- Motion blur
- On/off
- Receive On/off
- Invert color


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
under the speed of Step sequencer A or B
- clear Drop down menu
- Open browser
- Drop down menu

