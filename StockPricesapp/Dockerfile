FROM openjdk:11
ADD target/StockPricesapp-0.0.1-SNAPSHOT.jar stockapp.jar
ENTRYPOINT ["java", "-jar", "stockapp.jar"]
EXPOSE 7777
ENV spring.datasource.url=jdbc:mysql://stockappdb.cnp9uj1dgu0f.ap-northeast-1.rds.amazonaws.com:3306/stockappdb