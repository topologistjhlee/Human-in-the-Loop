# Human-in-the-Loop

# (컨테이너 설치, node.js 설치 생략)



### sql 서버 컨테이너 실행
user@DESKTOP-B8Q6EDG:/mnt/c/Windows/System32$ docker run -d \
  --name vss-db \
  -p 3307:3306 \
  -e MYSQL_ROOT_PASSWORD=wngus469@ \
  -e MYSQL_DATABASE=vss_inventory \
  mysql:8.0


