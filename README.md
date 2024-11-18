# Revival-Of-90s-and-80s-House-and-Dance-Trance

# General Information
My prototype was a project that i was motivated to create in order to revive the 80-90s house and dance trance that was noted as one of the best outlets for promoting self-expression and uniting communities. Most music currently focuses on retaining the biggest profit margin or getting what they assume to be the best reaction instead of considering what is needed by individuals. My goal was create a 80-90s inspired house track that transcended individuals back in time and to promote the self-expression and unity of community that has been missing for far too long. My purpose was to remind individuals why the music was better in the past. To bring individuals back to the dance floor.

# Technologies Used
I used my Microsoft Surface Pro 7 to download the software of SonicPi. 
Sonic Pi utilises the coding language of Ruby. 
Sonic Pi v4.5.1 On Windows 

# Features
Cross-Platform 
Ruby coding Language 
A House and Trance Musical Composition That is inspired by heavy drum introductions, soulful elements, disco-style beats and carefully constructed sequences that made 80-90s house and dance trance burst with spirt and unite community through self-expression. 
This Can be used to introduce individuals back into the desirable scene of 80-90s house trance and dance. 
There is multiple layering of loops in this musical composition that are timed through the use of In thread loops, manipulation by 'Amp' and 'Rate' and the strucutral function of sleep. 
Sleep as a command to triggering a rest between my samples, play notes and synths was essential in increasing or decreasing the tempo and sequence of my composition. Being able to control and manipulate the rest between beats by a small or large margin was essential in building melody and eventually creating a drop. 

# Screenshots 
![Screenshot (757)](https://github.com/user-attachments/assets/cb4ee991-179d-49b8-9e27-6a2717137e18)
![Screenshot (759)](https://github.com/user-attachments/assets/0087d80f-ecdd-459c-bcb9-225d0f74762a)
![Screenshot (755)](https://github.com/user-attachments/assets/3fbc67b3-ff1b-455d-884a-2845f5a7887d)
![Screenshot (762)](https://github.com/user-attachments/assets/12c7216b-bbc7-4577-9558-301c61c35b87)


# Set Up 
This project requires the user to have access to the cross platform softwares of Mac, Windows, Linux and Raspberry Pi. 
Once you have one of these accesible the next requirment is to install the software if necessary. 
Once Placing this code into the software and hitting run you will hear the track begin to play. In order to end it once the loops have started you must press stop. It is reccomended that the loops are played for 10 seconds minimum. 
If you are wanting to start the process yourself, The essential contribution to creating a 80-90s house trance and dance track is to utilse samples in SonicPi and manipulate these to be repurposed to your own unique productions through Amp, rate, Threads and Synths. 
The tutorial offered by SonicPi on the interface is extremely useful when introducing yourself to code and making positve progression in skill. 


# Usage 

#Begin Electronic Beat Progression
use_synth :bass_foundation
play 38
sleep 0.70
play 50
sleep 0.70
play 62
sleep 0.70
play 38
use_synth :bass_foundation
play 50
use_synth :bass_foundation
play 74
play 50
sleep 0.70
play 62
sleep 0.70
use_synth :bass_highend
play 38
use_synth :bass_foundation
use_synth :bass_foundation
play 38
sleep 0.50
play 50
sleep 0.50
play 62
sleep 0.50
play 38
use_synth :bass_foundation
play 50
use_synth :bass_foundation
play 74
play 50
sleep 0.50
play 62
sleep 0.50
use_synth :bass_highend
play 38
use_synth :bass_foundation
play 38
sleep 0.40
play 50
sleep 0.40
play 62
sleep 0.40
play 38
use_synth :bass_foundation
play 50
use_synth :bass_foundation
play 74
play 50
sleep 0.40
play 62
sleep 0.40
use_synth :bass_highend
play 38
use_synth :bass_foundation
use_synth :bass_foundation
use_synth :bass_foundation
play 38
sleep 0.30
play 50
sleep 0.30
play 62
sleep 0.30
play 38
use_synth :bass_foundation
play 50
use_synth :bass_foundation
play 74
play 50
sleep 0.30
play 62
sleep 0.30
use_synth :bass_highend
play 38
use_synth :bass_foundation
use_synth :bass_foundation
play 38
sleep 0.20
play 50
sleep 0.20
play 62
sleep 0.20
play 38
use_synth :bass_foundation
play 50
use_synth :bass_foundation
play 74
play 50
sleep 0.20
play 62
sleep 0.20
use_synth :bass_highend
play 38
use_synth :bass_foundation
#Begin Heavy Drum Kicks 
8.times do
  sample :bd_tek
  sleep 0.4
end
sleep 0.01
8.times do
  sample :bd_zome
  sleep 0.4
end
sleep 0.01
8.times do
  sample :bd_sone
  sleep 0.4
end
sample:drum_heavy_kick
sleep 0.4
sample :drum_heavy_kick
sleep 0.4
sample :drum_heavy_kick
sleep 0.4
sample :drum_heavy_kick
sleep 0.4
sample :drum_heavy_kick
sleep 0.200
sample :drum_heavy_kick
sleep 0.200
sample :drum_heavy_kick
sleep 0.200
sample :drum_heavy_kick
sleep 0.200
sample :drum_heavy_kick
sleep 0.4
sample :drum_heavy_kick
sleep 0.4
sample :drum_heavy_kick
sleep 0.4
sample :drum_heavy_kick
sleep 0.4
sample :drum_heavy_kick
sleep 0.4
sample :drum_heavy_kick
sleep 0.4
sample :drum_heavy_kick
sleep 0.200
sample :drum_heavy_kick
sleep 0.200
sample :drum_heavy_kick
sleep 0.200
sample :drum_heavy_kick
sleep 0.200
sample :drum_heavy_kick
sleep 0.200
sample :drum_heavy_kick
sleep 0.200
#Introduce Melody
sample :loop_industrial
sleep 0.877
sample :loop_industrial
sleep 0.877
sample :loop_industrial
sleep 0.877
sample :loop_industrial
sleep 0.877
sample :loop_industrial
sleep 0.877
sample :loop_industrial
sleep 0.877
sample :elec_filt_snare, rate: 0.90
sample :loop_industrial
sleep 0.877
sample :loop_industrial
sleep 0.877
sample :loop_industrial
sleep 0.877
sample :loop_industrial
sleep 0.877
sample :loop_industrial
sleep 0.877
sample :elec_filt_snare, rate: 0.90
sample :loop_industrial
sleep 0.877
sample :loop_industrial

#Begin Loops for drop
in_thread do
  loop do
    sample:loop_amen_full
    sleep  6
  end
end

in_thread do
  loop do
    sample :ambi_choir, rate: 0.7, amp: 0.5
    sleep 6.8
  end
end

in_thread do
  loop do
    sample :guit_em9, rate: 1.7
    sleep 6.9
  end
end

# Project Status
This Project is compelte for the basis of the A2 prototype however there is definatly areas where i wish i imporved. 

# Room for Improvement
1. Introducing more layering to advance the technicality of my coding however i didn't find it easy to seemingly blend the intensity of the samples and plays that i was introducing.
2. Adding a form of vocals to adhere to the soulful elements and talking elements that are incoporated in a range of 80-90s house and dance trance.
3. Using the features of Pan and attack/release would have added immense value to the layering of my syntax and structure however when attempting to introduce these features they were not working at the time.


# Acknowledgments 
This project was inspired by particular songs that have resonated with me from the 80-90s era. These songs include 
Blue Monday - New order 
Insomnia - Faithless 
No good - The prodigy 
9PM (Till i Come) - ATB
Can't Stop Raving - Dune
The software of SonicPi itself and the vast sample's it provides to be repurposed into unique new sounds. Not only the interface ease of accesibility but the tutorial and resources provided though SonicPi, More specfically the Sam Aarons Code Music WIth Sonic Pi The MagPi Essentials. The Article was detailed and provided great expertise that helped progress not only my project but my learning and understanding of code. 

# Contact 
Created By Scarlet Andrews Bromage 
email - Scarlet.andrews@student.uts.edu.au
