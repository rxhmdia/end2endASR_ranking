## End-to-End ASR Ranking
This repository is inspired by

WER and CER are summarized.


### TIMIT
| PER | Paper | Published | Notes |
| :-- | :---- | :-------- | :---: |
| 18.2 | [Towards End-To-End Speech Recognition with Deep Convolutional Neural Networks](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/1446.PDF) | Interspeech 2016 (2016/9) | CNN-CTC (maxout) |
| 18.3 | [Speech recognition with deep recurrent neural networks](https://arxiv.org/abs/1303.5778) | ICASSP 2013 (2013/4) | RNN Transducer |
| 18.4 | [Speech recognition with deep recurrent neural networks](https://arxiv.org/abs/1303.5778)  | ICASSP 2013 (2013/4) | BLSTM-CTC (BLSTM250-5L) |
| 18.6 | [Speech recognition with deep recurrent neural networks](https://arxiv.org/abs/1303.5778)  | ICASSP 2013 (2013/4) | BLSTM-CTC (BLSTM250-3L) |
| 18.9 | [Towards End-To-End Speech Recognition with Deep Convolutional Neural Networks](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/1446.PDF) | Interspeech 2016 (2016/9) | CNN-CTC (PReLU) |
| 19.3 | [Towards End-To-End Speech Recognition with Deep Convolutional Neural Networks](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/1446.PDF) | Interspeech 2016 (2016/9) | CNN-CTC (ReLU) |
| - | Paper | Published | Notes |



### Librispeech
| WER (test-clean) | WER (test-other) | Paper | Published | Notes |
| :--------------- | :--------------- | :---- | :-------- | :---: |
| * | * | Paper | Published | Notes |


### CSJ (Corpus of Japanese)
#### Fullset (about 600h)
| CER (eval1) | CER (eval2) | CER (eval3) | Paper | Published | Notes |
| :---------- | :---------- | :---------- | :---- | :-------- | :---: |
| 7.9 | 5.8 | 6.7 | Paper | Published | Joint CTC-Attention + join dec. (one-pass) + RNNLM (seperate) |
| 8.4 | 6.2 | 6.9 | Paper | Published | Joint CTC-Attention (BLSTM encoder 320*6 layers) + join dec. (one-pass) |
| 9.4 | 7.3 | 7.5 | Paper | Published | CTC-syllable |
| 9.5 | 7.0 | 7.8 | Paper | Published | Joint CTC-Attention (BLSTM encoder 320*5 layers) |
| 10.0 | 7.1 | 7.6 | Paper | Published | Joint CTC-Attention + joint dec. (one-pass) |
| 10.1 | 7.1 | 7.8 | Paper | Published | Joint CTC-Attention + joint dec. (rescoring) |
| 10.5 | 7.6 | 8.3 | Paper | 2017/3 | Joint CTC-Attention (Interspeech 2017) |
| 10.9 | 7.8 | 8.3 | Paper | Published | Joint CTC-Attention (BLSTM encoder 320*4 layers) |
| 11.4 | 7.9 | 9.0 | Paper | Published | Attention (Interspeech 2017) |
| 11.5 | 7.9 | 9.0 | Paper | Published | Attention (ASJ) |
| * | * | * | Paper | Published | Notes |

#### Subset (about 240h)
| CER (eval1) | CER (eval2) | CER (eval3) | Paper | Published | Notes |
| :---------- | :---------- | :---------- | :---- | :-------- | :---: |
| 13.9 | 10.2 | 22.2 | Paper | 2017/3 | Joint CTC-Attention (eval3 is domain mismatch) |
| 17.2 | 12.4 | 25.4 | Paper | 2017/3 | Attention (eval3 is domain mismatch) |
| * | * | * | Paper | Published | Notes |


### Switchboard
#### 300h
| WER | Paper | Published | Notes |
| :-- | :---- | :-------- | :---: |
| * | Paper | Published | Notes |

#### 2000h (+ Fisher)
| WER | Paper | Published | Notes |
| :-- | :---- | :-------- | :---: |
| * | Paper | Published | Notes |


### WSJ
| WER | Paper | Published | Notes |
| :-- | :---- | :-------- | :---: |
| * | Paper | Published | Notes |
