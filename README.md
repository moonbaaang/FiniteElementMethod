![GitHub branch checks state](image/main)

# 동해 형성에 대한 유한 요소 수치 모형 제작과 형성 가설의 입증

> 강원대학교 지구물리학과 판구조 · 지구동역학 연구실
>
> *Advisor* 지도교수 소병달
>
> *teammate* 장민석 문병전 홍윤서

![aspect](image/aspect.jpg)

### ASPECT

> Download Link : [ASPECT](https://geodynamics.org/cig/software/aspect/)

* 2D 및 3D 모델에서 열 대류 문제를 수치 모사하기 위한 유한 요소 병렬 코드
* 코드의 주 목적은 지구 맨틀의 수치 모사에 있지만 다양한 모형에도 적용 가능
* 복잡한 문제를 해결하기 위한 코드 확장성이 특징으로 동해의 열개 현상과 같은 지구동역학적 모형 제작에 용이함

### Docker

![docker](image/docker.jpg)

* Particle tracing 기법 사용 시 많은 Particle을 설정하기에  적은 횟수의 연산으로도 큰 용량을 차지하여 하드디스크 용량이 부족해질 수 있음
* 이때 docker를 이용해 독립적인 컨테이너를 생성하여 내부에서 aspect를 동작시킴으로 문제를 해결

> docker 내부에서의 ASPECT 설치 및 실행 방법은 [여기](http://www.math.clemson.edu/~heister/manual.pdf)를 참조 

