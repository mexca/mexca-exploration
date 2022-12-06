# MEXCA Exploration
This repository is dedicated to storing and sharing code for exploring software that could be used in the [MEXCA](https://github.com/mexca) project. It contains notebooks that explore or test different software packages:

- [OpenFace](https://github.com/TadasBaltrusaitis/OpenFace): C++ library for detecting faces and facial features, such as landmarks and action units. Is also available as a Docker container. We decided to discard this library because it has a non-permissive license.
- [openSMILE](https://audeering.github.io/opensmile-python/): C++ library and Python package for extracting voice features from audio. We decided to discard the library and package because of their non-permissive licenses.
- [SpeechBrain](https://speechbrain.github.io/index.html): Python package for speech applications. Can perform voice activity detection, speaker diarization, and identification.
- [Whisper](https://github.com/openai/whisper): Python package for Automatic Speech Recognition. Can perform speech transcription, language detection, and translation for a large number of languages.

These tools are explored using the test files in the `audio/` and `video/` folders and the [AMI](https://groups.inf.ed.ac.uk/ami/corpus/) corpus. The tests are performed on a currently not-publicly available data set of the Dutch election debate 2021 (see this [blog post](https://stukroodvlees.nl/welke-lijsttrekkers-lacht-het-meest-en-hoe/) for details). 

## Directories
- `audio/`: Audio files for exploring libraries.
- `speaker_id_model/`: Model and data files for training and fine-tuning a SpeechBrain speaker recognition model.
- `video/`: Video files for exploring libraries.
