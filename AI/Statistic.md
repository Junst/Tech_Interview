# Statistic / Probability
 ## 질문 리스트
- 1-0. **Central Limit Theorem이란 무엇인가요?**

  1-1. **Central Limit Theorem은 어디에 쓸 수 있을까요?**

  1-2. **큰 수의 법칙이란 무엇인가요?**

  1-3. **확률이랑 통계랑 다른 점은 무엇인가요?**
  
  1-4. **Marginal Distribution이란 무엇인가요?**
  
  1-5. **Conditinal Distribution이란 무엇인가요?**
  
  1-6. **Bias란 무엇인가요?**
  
    Bias는 어느 한쪽으로 치우쳐 있다는 상태를 나타내는 편향이라는 의미의 단어이다. 
    Machine Learning의 목적은 데이터로부터 패턴을 익히고 관찰하지 못한 새로운 데이터에 대해서 예측하기 위한 모델을 훈련한다.
    데이터셋에 맞게 모델의 파라미터 θ를 훈련하는 것이다. 이 θ가 모델로부터 만들어진 각 데이터셋 D로부터 모델의 파라미터 ^θ를 추정하고 평균을 낸다.
    이 값이 실제 모델의 파라미터와 발생하는 차이를 Machine Learning에 정의하는 bias라고 합니다.
  
  1-7. **Biased / Unbiased Estimation의 차이는 무엇인가요?**
  
    Biased Estimator는 파라미터 추정 평균의 bias 값이 0이 아닌 경우를 말하고, Unbiased Estimator는 파라미터 추정 평균에 대해서 bias 값이 0인 경우를 말한다.
    이 둘을 구분하는 이유는, Bias가 추정된 파라미터끼리의 차이와 무조건 정비례하지 않기 때문이다.
    
  1-8. **Bias, Variance, MSE란 무엇인가요? 그리고 그들의 관계를 설명하시오.**
  
    Bias는 추정값의 평균과 참 값들 간의 차이를 의미하며, Variance는 추정 값들의 흩어진 정도를 의미한다.
    예를 들어, Train data가 Bias를 낮추기 위해 모델 복잡도를 높이면 Variance(분산)이 커져 Overfitting이 일어날 수 있다.
    반대로 Variance를 낮추면, bias가 커지는 과소적합이 일어난다. 이렇게 서로 상반된 관계를 보이는 이 두 개를 bias-variance trade off라고 부른다.
    둘 중 하나를 낮추려고 해도, 다른 한쪽이 올라가 Total loss가 증가한다. 
    여기서 최적의 모델 복잡도는 bias와 variance가 교차하는 부분에서 MSE 혹은 total test loss(bias와 variance의 합)가 가장 작은 복잡도를 가지는 것이다.
    MSE(Mean Square Error, 평균 제곱 오차)는 반대로 읽으면 '오차'를 '제곱'한 값의 '평균'을 내봄으로 정확도를 측정하는 방법이다.
    실제 관측값과 모델이 예측하는 값의 차이(오차)를 제곱한 후 모두 더해 평균을 구한다.
  
  1-9. **Sample Variance란 무엇인가요?**
  
  1-10. **Variance를 구할 때, N 대신에 N-1로 나눠주는 이유는 무엇인가요?**
  
  1-11. **Gaussian Distribution에서 MLE와 Sample Variance 중에 어떤 걸 사용해야 하는가요?**
  
  1-12. **Unbiased Estimation은 무조건 좋은가요?**
  
  1-13. **Unbiased Estimation의 장점은 무엇인가요?**
  
- 2-1. **Binomial, Bernoulli, Multinomial, Multinoulli란 무엇인가요?**

  2-2. **Beta Distribution과 Dirichlet Distribution이란 무엇인가요?**
  
  2-3. **Gamma Distribution은 어디에 쓰이는가요?**
  
  2-4. **Possion distribution은 어디에 쓰이는가요?**
  
  2-5. **Bias and Varaince Trade-Off 란 무엇인가요?**
  
    위의 답변 참조. 추가적으로, MSE는 Bias의 제곱과 Variance의 합으로 전개가 가능하다. 
  
  2-6. **Conjugate Prior란?**
  
- 3-1. **Confidence Interval이란 무엇인가요?**

  3-2. **covariance/correlation 이란 무엇인가요?**
  
  3-3. **Total variation 이란 무엇인가요?**
  
  3-4. **Explained variation 이란 무엇인가요?**
  
  3-5. **Uexplained variation 이란 무엇인가요**
  
  3-6. **Coefficient of determination 이란? (결정계수)**
  
  3-7. **Total variation distance이란 무엇인가요?**
  
  3-8. **P-value란 무엇인가요?**
  
  3-9. **likelihood-ratio test 이란 무엇인가요?**
