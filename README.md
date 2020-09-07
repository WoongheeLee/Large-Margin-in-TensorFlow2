# Large-Margin-in-TensorFlow2

## 목적

[Large Margin Deep Networks for Classification](https://arxiv.org/abs/1803.05598) 에서 제안한 loss 구현 확인용 노트북

## 방법
* MNIST 데이터 사용
* CNN + Fully connected 로 이루어진 classification 모델
* large margin loss 구현
  * 최종 softmax 에만 적용
  * hidden layer에는 loss 적용 안함

## 시각화
* 최종 레이어 바로 이전 레이어의 latent를 시각화

**그냥 l2 로스 씀**
![fig1](./img/l2-loss.PNG)

**large margin loss 적용**
![fig2](./img/large-margin-loss.PNG)