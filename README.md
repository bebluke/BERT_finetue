# BERT_finetue 
```
Sentiment Multiclass Classification of Short Chinese Sentences
```

## Training Data 
- [Datasets:Johnson8187/Chinese_Multi-Emotion_Dialogue_Dataset](https://huggingface.co/datasets/Johnson8187/Chinese_Multi-Emotion_Dialogue_Dataset)

## Base Model
- [google-bert/bert-base-chinese](https://huggingface.co/google-bert/bert-base-chinese)

## Installing
```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126
pip3 install -r requirements.txt
```
# Versioning
```
Python 3.12.7
```

| Package Name | Version  |
|--------------|----------|
| torch | 2.6.0+cu126 |
| torchvision | 0.21.0+cu126 |
| torchaudio  | 2.6.0+cu126 |
| transformers | 4.48.3 |
| datasets | 3.2.0 |
| evaluate | 0.4.3 |
| accelerate | 1.3.0 |
| scikit-learn | 1.5.1 |

## Describe
The emotions are divided into 8 categories as below. After finetune, enter the text and the model will classify it.
```
"平淡語氣": 0
"關切語調": 1
"開心語調": 2
"憤怒語調": 3
"悲傷語調": 4
"疑問語調": 5
"驚奇語調": 6
"厭惡語調": 7
```
## Result
...
[影片名稱或其它標題](你的影片連結)
...

## Others
...
...
