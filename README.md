# demo
간단하게 hello world를 출력하는 코드입니다. commit을 통해 cloud에 자동으로 반영되는 것을 보여주고자 하는 내용입니다.
이전 버전으로의 Rollback도 쉽게 할 수 있고, Traffic 관리, log 관리도 가능하다.

# How

github/workflows/google-cloudrun-docker.yml 에서 

사용자에 맞는 값 설정

GCP 에서 service account를 만들고 비밀 키를 받아 그 비밀키를 가져와 설정한다.

