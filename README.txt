1. Install docker
2. Create a working folder (e.g. guidegen)
3. Download the following two folders from the Github repo into the working directory: upload and users (git clone https://github.com/hotomski/guidegen.git)
4. Execute the following command to run the container:  docker run -it --rm -v pathToTheUploadFolder:/data/upload -v pathToTheUsersFolder:/data/users -p 80:8080 sofijahotomski/guidegen:latest
5. Open your web browser and type: localhost/guidegen
6. Have fun with GuideGen!