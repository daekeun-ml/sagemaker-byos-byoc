## Amazon
Amazon SageMaker는 머신 러닝 모델을 훈련하고 배포하기 위해 
도커 컨테이너(Docker container)를 사용합니다. SageMaker에서 현재 지원하고 있지 않는 알고리즘이나 머신 러닝 프레임워크, 또는 여러분이 로컬 환경에서 개발한 모델이라도 도커 컨테이너를 ECR에 등록 후, SageMaker에서 훈련하고 배포할 수 있습니다.

본 핸즈온에서는 Scikit-learn 및 TensorFlow 프레임워크 상에서 작성된 모델을 컨테이너로 패키징합니다. 

보다 자세한 내용을 AWS의 공식 블로그에서 확인할 수 있습니다.
