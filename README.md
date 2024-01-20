This project aids Technology companies in the Cyber Security industry in the recognition of fake spoken audio.
- Leveraged the TTS library and pre-trained available models to create a voice cloning system that, starting from a text and a voice sample, creates fake audios.
- Evaluated the Fake Audio generation pipeline performance using Word Error Rate. The average WER in the fake audio generated is 0.3
- Used the Speech2TextProcessor of the transformer library to identify the text of the generated fake audios. Based on such text, the Word Error Rate was computed
- Created a deep neural network with convoluted and dense layers to determine synthetically generated audio.
- Tested the created model on the TIMIT dataset (for ground truth) and on the generated Fake audios. Reached a F1 score of 0.9988

Curious for more? Check out the Notebook in the repo
