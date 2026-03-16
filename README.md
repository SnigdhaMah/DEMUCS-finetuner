# Waveform Music Separation
Audio splitting is a useful feature for music production, yet it is a task that humans cannot do alone. Deep learning is increasingly being used in multimodal applications, with audio application of ML at the forefront. Research has been done on audio splitting through image separation (spectrogram) yet little research has been successful on (pure audio) waveform data.

We sought to test whether we could create a model that could separate audio into more than the standard 4 stems, by finetuning the [DEMUCS separation model](https://github.com/facebookresearch/demucs?tab=readme-ov-file) [Alternative Link](https://github.com/adefossez/demucs). To do so, we used the [Moises Db dataset](https://github.com/moises-ai/moises-db).

## How to Run
Clone the repository locally and use the Google Colab extension to run. If run locally, you will need to ignore cells that deal with Google Drive Setup.

You may use the finetuner weights we ended with as stored in `finetuner_weights.pth` to start you own training of the DEMUCS model, though you may need to modify file paths to access it from the notebooks.
