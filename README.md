Dockerfile
    이미지를 만드는 절차에 대한 정의

    docker build -t 이미지이름(컨터이너 저장소/계정명/이미지명:태그-버전) Dockerfile 경우(. - 같은 경로) 
docker-compose.yml
    - 여러개 이미지를 컨테니어로 배포 
    - 이미지간의 순서, 세부 설정 
    - 파이썬이 필수 설치가 되어 있어야 한다.


gradle bootBuildImage : Dockerfile, compose.yml 파일을 생성하지 않아도 알아서 이미지로 빌드해 주는 명령어


gradle build : gradle test -> gradle package .. 
gradle bootJar : 테스트 진행없이 실행 가능한 jar


