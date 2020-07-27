Transfer Learning Basic
========================

Transfer Learning에 대해서 알아보자.

Transfer learning is the process of:
1. Taking a network pre-trained on a dataset
2. And utilizing it to recognize image/object categories it was not trained on

two types of transfer learning
1. Transfer learning via feature extraction
 - Fully Connected Layer 바로 전(즉, Flatten 하기 전까지의 layer = bottleneck layer)만 가지고 와서 우리가 원하는 레이어(classification layer = FC layer)를 추가
 - 즉, 사전에 학습된 feature data를 그대로 사용 (학습시키지 않음, 추가한 FC layer만 학습)
 
2. Transfer learning via fine-tuning
 - 추가한 FC layer를 포함하여 사전에 학습된 feature data(즉 bottleneck layer)까지 같이 학습
