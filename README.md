AWS CODESTAR
=

### 서버리스?  

- 서버에 대한 고민 없이 애플리케이션을 구축 및 작동  
- 서버리스는 그 단어의 뜻처럼 서버가 없는것이 아니라 서버가 없는것 처럼 세팅이 간편해지고 있다는 뜻이다.  
    
![serverless](/images/serverless.PNG)  


### serverless computing의 이점

![positive](/images/positive.PNG)   

### 서버리스 오픈소스 프레임워크를 통한 자동 배포

- 그렇다면 이를 어떻게 하면 쉽게 코드만 작성해서 배포까지 할수 있게 되었는가?  

![framework](/images/framework.PNG)   

- 오픈소스 프레임워크들이 생겨나고 있고, AWS 에서도 이를 만들게 된것이 AWS SAM (serverless applicatioln model)이다.   
- CloudFormation 기반이고, 람다함수와 기타 리소스도 배포하며, 정해진 템플릿에서 공개표준기반 (아파치2.0)으로 만들어졌다.  

### 일반적인 개발 및 배포 단계

- 일반적으로 개인이 혼자서 서버리스 앱을 만들고 개발 배포하는것이 쉬운것은 아니다.   

![normal](/images/normal.PNG)   

### AWS 기반 개발 및 배포 단계 - 통합 개발환경

- codestar와 c9으로 빠르게 서버리스 개발 및 배포 환경구축  
- 클라우드 기반 IDE를 통한 개발 협업  
- 바로 앱 패키징 및 자동 배포 가능  

![aws_dev](/images/aws_dev.png)   

### 서버리스 아키텍처 - 주요 AWS 빌딩 블록 

- 추가적으로 몇가지의 AWS 빌딩 블록들도 있는것을 알고있다면 좋다.  

![block](/images/block.PNG)   

### 서버리스 앱 개발 및 배포 과정 

* AWS CodeStar로 샘플 앱 프로젝트 (API 호출 시 간단한 HTML 파일 출력) 배포  
* 소스코드, 빌드, 배포 및 파이프라인 서비스 살펴보기
* 각종 AWS 리소스 생성 내역 확인하기
* AWS Cloud9 기반 클라우드 IDE로 수정 및 배포하기

### 데모 시작! 

#### [전반부](demo1.md)
#### [중반부](demo2.md)
#### [후반부](demo3.md)

### 자료 출처

- AWS 2018 online conference - AWS CodeStar 및 Cloud9을 통한 서버리스(Serverless) 앱 개발 길잡이  
 의 ppt 자료와 node.js demo를 활용해 ROR demo로 변경 하였습니다. 
- 1105 AWS 201 Serverless 세미나의 ppt 자료를 일부 활용하였습니다.
