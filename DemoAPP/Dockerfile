FROM eclipse-temurin:17-jdk-alpine

WORKDIR /app

COPY target/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]

# FROM openjdk:17-jdk-slim
# WORKDIR /app
# COPY target/*.jar app.jar
# EXPOSE 8080
# ENTRYPOINT ["java","-jar","app.jar"]


# username: rohitkumar4praja
#Password: Rohit@123#

# - name: Login to Docker Hub
#   run: echo "${{ secrets.DOCKER_PASSWORD }}" | docker login -u "${{ secrets.DOCKER_USERNAME }}" --password-stdin

# - name: Tag Image
#   run: docker tag demo-app:${{ github.run_number }} yourusername/demo-app:${{ github.run_number }}

# - name: Push Image
#   run: docker push yourusername/demo-app:${{ github.run_number }}


