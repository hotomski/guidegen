1. install docker
2. create a working folder (e.g. guidegen)
3. download the following two folders from github into the working directory: upload and users (git clone https://github.com/hotomski/guidegen.git)
4. execute docker run -it --rm -v pathToTheUploadFolder:/data/upload -v pathToTheUsersFolder:/data/users -p 80:8080 sofijahotomski/guidegen:latest
5. open your web browser and type: localhost/guidegen
6. Have fun with GuideGen!