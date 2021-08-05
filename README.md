# GAN
GAN(Generative Adversarial Network-생산적 적대 신경망)

> *GAN(Generative Adversarial Network-생산적 적대 신경망)
-Generative: “생산하는” 이라는 뜻으로 GAN모델 안에서의 의미는 ‘이미지를 생성한다’라는 의미이다.



> -Adversarial: “적대적인”이라는 뜻으로, 서로 경쟁하면서 무엇인가를 좋게 한다는 의미.



> 즉, 이미지를 만들기는 하는데, 서로 경쟁하면서 좋게 만든다. 라는 의미이다.
-따라서 전반적인 생산적 적대 신경망 GAN의 의미는 서로 경쟁하면서 가짜 이미지(생성자)를 진짜 이미지와 최대한 비슷하게 만들어내는 네트워크를 말하게 되는 것이다.



![image](https://user-images.githubusercontent.com/78295968/128275971-4537cabf-e267-4e00-9556-af1651088157.png)
> 위의 그래프를 보면 우측으로 갈 수 록 생성자가 만들어낸 분포도와 실제 데이터의 분포도가 같아진다. 이러한 결과를 얻는 것이 GAN의 목적이다.


![image](https://user-images.githubusercontent.com/78295968/128276015-3b3cea05-8071-4143-ae14-fe3269f15230.png)

> 위의 그래프와 같이 목적을 얻기 위한 목적 함수.


> 이 소스 코드는 위와 같이 GAN을 구성하는 코드를 구현한 것이다.
