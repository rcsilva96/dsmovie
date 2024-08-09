# Use uma imagem base do Java
FROM openjdk:17-jdk-slim

# Define o diretório de trabalho dentro do contêiner
WORKDIR /app

# Copia o arquivo JAR do projeto para o contêiner
COPY target/*.jar app.jar

# Expõe a porta na qual a aplicação irá rodar
EXPOSE 8080

# Define o comando para executar a aplicação
CMD ["java", "-jar", "app.jar"]
