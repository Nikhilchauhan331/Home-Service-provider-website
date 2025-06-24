Pre-requisites : 
	1. Install nodejs and npm (if already have , then skip).
		- download and install from this url :  https://nodejs.org/en/download/prebuilt-installer .

		- run commands to check version if it installed correctly : ' node -v ' & ' npm -v ' .

	2. MondoDB :
		- download and install from this url : https://www.mongodb.com/try/download/community .

		- add your mongodb connection string in evn file in server folder , if want.

		   !-- MONGODB_URI= ' here goes your mongodb string ' --! (string should be in quotes).
	optional :
	-you can add your jwt_secret_key in env file in server folder .

Steps to run code :

1. download zip file and extract to new folder.

2. open folder in vscode and 

3. open client folder in terminal.
	- type in terminal : ' npm install ' (as given in quotes , without quotes ) .
	  then type : ' npm run dev ' .

4. open server folder in another new terminal.
	- type in terminal : ' npm install ' (as before ) .
	  then type : ' npm run start ' .

5. then open link generated in client folder terminal .
	
