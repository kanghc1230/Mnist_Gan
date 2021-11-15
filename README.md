https://colab.research.google.com/github/kanghc1230/Mnist_Gan/blob/main/Mnist_GAN.ipynb

# 적대적 생성 신경망GAN (Generative adversarial network)

GAN이라는 신경망은 2개의 신경망으로 구성되어 있다.. 판별자 신경망과 생성자 신경망으로 나뉜다.
생성자는 아무런 의미가 없는 그림에서 진짜처럼 그럴듯한 가짜 그림을 생성할 수 있으며, 판별자는 진짜 그림과 생성자가 만든 가짜 그림을 구별할 수 있다. 생성자는 판별자가 진짜처럼 생각하도록 만드는것이 목표이며, 판별자는 생성자가 진짜인지 가짜인지 다 구별하는것이 목표이다. 결론적으로 두 개의 신경망을 사용하여 새로운 그림을 생성해 내는 기법이 바로 적대적 생성 신경망이라 할 수 있다.


## 적대적 인공지능으로 숫자 생성

![image](https://user-images.githubusercontent.com/85793624/141706554-48a4d4f3-6f88-4314-abc9-4a607976824c.png)

