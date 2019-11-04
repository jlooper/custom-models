# Custom models

Use these models in your projects that require quantized TensorFlow Lite models, such as for the Google Coral Board or NativeScript-Vue projects that use the Firebase plugin to do inference using custom-trained models.

The system for training is adapted from TensorFlow's [TF-Slim high-level API](https://github.com/jlooper/models/tree/master/research/slim); I forked the Research folder from their samples to make it easier to retrain on custom data. 

The data in the /booze and /cheese images are scraped from searches in Firefox and images exported from videos that I filmed with my iPhone using ffmpeg to extract images from video. The /birds images are from the Cornell Ornithology Lab's dataset of [North American Songbirds](https://dl.allaboutbirds.org/nabirds).
