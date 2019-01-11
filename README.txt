1. Install docker
2. Create a working directory (e.g. guideGenRepo)
3. Download the content of the Github repo into the working directory: git clone https://github.com/hotomski/guidegen.git (the upload and users folders that are downloaded are going to be used in the next step)
4. Execute the following command to run the container:  docker run -it --rm -v pathToTheUploadFolder:/data/upload -v pathToTheUsersFolder:/data/users -p 80:8080 sofijahotomski/guidegen:latest (replace pathToTheUploadFolder and pathToTheUsersFolder with the actual paths on your computer)
5. Open your web browser and type: localhost/guidegen
6. Have fun with GuideGen! You can sign up or use the following two existing users:
	- to log in as a requirements engineer use the credentials of Anna Scott:
		username: anna.scott
		password: annascott
	- to log in as a test engineer use the credentials of John Mayer:
		username: john.mayer
		password: johnmayer
   
You can upload the list of example requirements from RequirementsExamples.xlsx or you can create your own list by using the same template.   