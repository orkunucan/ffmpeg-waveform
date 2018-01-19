# ffmpeg-waveform

You can use the following code to create waveform images with color and size.


    ffmpeg -i SampleAudio_0.4mb.mp3 -filter_complex "showwavespic=s=1920x200:colors=#ff9500" -frames:v 1 SampleAudio_0.4mb.png
    
    ffmpeg -i SampleAudio_0.7mb.mp3 -filter_complex "showwavespic=s=1920x200:colors=#f7f7f7" -frames:v 1 SampleAudio_0.7mb.png
