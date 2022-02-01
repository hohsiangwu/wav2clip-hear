# HEAR 2021 NeurIPS Challenge: Wav2CLIP

https://neuralaudio.ai/hear2021-holistic-evaluation-of-audio-representations.html

## Installation

```
pip install git+https://github.com/hohsiangwu/wav2clip-hear.git
```

## Usage

### Scene Embeddings
```
import wav2clip_hear

model = wav2clip_hear.load_model("")
embedding = wav2clip_hear.get_scene_embeddings(audio, model)
```

### Timestamp Embeddings
```
import wav2clip_hear

model = wav2clip_hear.load_model("")
embedding, timestamp = wav2clip_hear.get_timestamp_embeddings(audio, model)
```

## Model Weights License
The model weights are made available under a [Creative Commons Attribution 4.0 International (CC BY 4.0) License](https://creativecommons.org/licenses/by/4.0/).
