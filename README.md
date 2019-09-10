이 자료는 책 "완벽한 IT인프라 구축을 위한 Docker" 에서 제공된 자료입니다.

Docker는 컨테이너 가상화 기술을 사용한 애플리케이션 실행환경 구축 및 운영플랫폼이다.

Dockerfile은 Docker 컨테이너의 기반이되는 Docker 이미지 구성정보가 담겨있는 파일이다.   　　
* CentOS 공식 이미지에 Apache HTTP Server를 설치
* 호스트 머신 80번 포트를 전송
* Bootstrap3.4에서 스타일링한 HTML 컨텐츠 샘플을 /var/www/html에 복사
 
Usage
------
    $ docker pull love7peace/docker:1.0
    $ docker run -d -p 8080:80 --name "testgit" love7peace/docker:1.0
    
    브라우저에 http://localhost:8080 을 입력하면 이미지 확인 가능.


### Docker 공식 사이트  
> https://www.docker.com/
>
