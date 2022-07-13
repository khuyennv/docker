# docker
 
- 1 install docker https://docs.docker.com/engine/install/
- 2 Copy .env.example to .env
- 3 Get uid and group id
    - Linux: id user_name
    - Mac: 
      - lấy uid: id -u
      - Lấy group id: id -g

- 4 Root folder run: docker-compose up --build

Sau khi chậy thành công sẽ được: phpmyadmin, redis, rabbitmq, redis
