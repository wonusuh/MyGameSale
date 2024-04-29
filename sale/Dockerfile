FROM amazoncorretto:17

COPY sale-0.0.1-SNAPSHOT.jar /app/test.jar

ENV APP_HOME /app
ENV MYSQL_IP=3.39.194.24
ENV MYSQL_PORT=3306
ENV MYSQL_DATABASE=gamesale
ENV MYSQL_USER=root
ENV MYSQL_ROOT_PASSWORD=1234
ENV MYAWS_IP=ec2-3-39-194-24.ap-northeast-2.compute.amazonaws.com

EXPOSE 8081

VOLUME /app/upload

WORKDIR $APP_HOME

ENTRYPOINT ["/app/entrypoint.sh"]
