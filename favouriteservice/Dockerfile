FROM java:8-jre
WORKDIR usr/src
ENV MYSQL_DATABASE=pubg_tournaments
ENV MYSQL_USER=root123
ENV MYSQL_PASSWORD=root
ENV MYSQL_CI_URL=jdbc:mysql://localhost:3306/pubg_tournaments
ADD ./target/favouriteservice-0.0.1-SNAPSHOT.jar /usr/src/favouriteservice-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","favouriteservice-0.0.1-SNAPSHOT.jar"]
