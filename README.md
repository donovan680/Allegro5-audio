# Allegro5-audio
For audio manipulation, Allegro provides the allegro_audio add-on. It is through this library that controls, allocation and other tasks related to audio. However, only it does not allow the use of audio formats. In addition, we use the allegro_acodec add-on, which gives us support for some formats like Ogg, Flac and Wave (no, unfortunately mp3 is not available).

To exemplify the use of audio files, let's make an application that will play a background song (in Ogg format) continuously and play a sample (in Wave format) when you press the spacebar.
