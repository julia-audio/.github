### JULIA_AUDIO

### TODO
1. create decoder (.mp3, .wav file format)
2. add spotify support

### STRUCTURE
```mermaid
graph TD
	AUDIO_FILE --> DECODER
	DECODER --> BUFFER
	BUFFER --> ALSA
	ALSA --> UI
	BUFFER --> AUDIO_PROCESSING
	AUDIO_PROCESSING --> BUFFER
```

audio processing
* audio speed manipulation
* "lofi" option
* pitch shift
* reverb, echo, chorus ...

### REPOS
[player][1]









[1]: https://github.com/julia-audio/player
