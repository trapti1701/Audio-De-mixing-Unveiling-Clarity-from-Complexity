# Audio Unmixer: Separating Sounds for Clarity
At a club party microphones picked up the following mixed signals: mix_{1-5}.wav

The original song recordings got lost, so the only existing copies are these mixed signals. 
In this program, I reconstructed the original songs using FastICA to unmix the audio. Then re-scaled the umixed signals from -1 to 1 and used wave.file.write to write out the unmixed signals.
