# todo-service

# Detta dokument beskriver stegen för att bygga, tagga och pusha Docker-image till Docker Hub. Följ dessa instruktioner för att ladda upp dina Docker-image.

# Bygg image för todo-service

1. Navigera till katalogen där din Dockerfile för todo-service finns:

# cd/todo-service

2. Bygg Docker-image:

# docker build -t ditt_användar_namn/todo-service-compose:1.0 . 

Säg till att du är In loggad på Docker Hub och använd ditt ditt_användar_namn på Docker Hub.

3. Tagga image:

# docker tag ditt_användar_namn/todo-service:1.0 ditt_användar_namn/todo-service-compose:1.0

4. Pusha image till Docker Hub:

# docker push ditt_användar_namn/todo-service-compose:1.0

Om du är inloggad på Docker Hub och klickar på Repositories så kan du kunna se imagen du har pushat upp.