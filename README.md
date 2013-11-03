# Espacializadores

This project was made 4 my research in multichannel spacialization during my graduation. It contains [PureData](puredata.org) patchs that spatialize any audio sources (as .wav, .aif) in surround systems like 5.1. Additionally, I add a special version of 10 channels.

The algorithms of spacialization (panoramization's curves) was made by Prof. Dr. J.A. Mannis at Art's Institute at Unicamp/Brazil (IA/Unicamp), and follow some principles of hearing, like natural perception of localization and acoustic shadows. These algorithms do not follow 5.1 surround system made by Dolby Surround

# Usage

Open the file MAIN.pd; I think the patch is quite intuitive, but if in doubt, at the top of MAIN.pd, there is an external object that opens audio files. Wav and. Aif. Stereo files will be mixed from the channels 1 and 2 to 1, 2, 3, 4, 5; mono files are mixed channel 1 for 1, 2, 3, 4, 5.

Start mix in the faders and hear the sound.

# TODO

- suport to mp3 and ogg files
- a graphical panner, better to gesture spacialization
