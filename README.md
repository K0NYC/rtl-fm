# rtl-fm

rtl-fm is a set of scripts that act as a wrapper for [**rtl_fm**](https://github.com/osmocom/rtl-sdr) and a few helper scripts for making listening to radio signals with SDR easy. For usage and available options see each script's 'usage' section. In addition to the wrapper and helper scripts the project includes 'node-red' based control panel that allows operating SDR dongles with the browser from everywhere. The dashboard is under development but works fine.

## Content 

### rtl-fm
**rtl-fm** is a wrapper script for [**rtl_fm**](https://github.com/osmocom/rtl-sdr). It extends the basic **rtl_fm** tuning with options such as playing, streaming to the network with VLC, sound activated recording, descrambling on the fly scrambled transmissions with [`deinvert`](https://github.com/windytan/deinvert) and starting AWS Transcribe jobs for recorded transmissions to get a transcript of the speech. 

### rtl-fm-stop
Helps to easily stop the **rtl_fm** and other piped/accompaying processes.

### rtl-fm-stream
Stream recorded mp3 files to the network for listening from a remote location with VLC.

### transcribe
Creates AWS Transcribe jobs for recorded files to get transcripts for the recorded speech.
