# Revival-Of-90s-and-80s-House-and-Dance-Trance
My project's Code 
# revival of house and trance

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

# Begin Loops
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


