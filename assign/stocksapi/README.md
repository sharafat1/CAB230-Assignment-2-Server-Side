This a server side application or an Express Application which provides

To install, install download the zip file, unzip the file. 

Then in the knexfile.js you will find this in the database_files folder. Open that and edit the password, and address for where the sql server is running and any other information which can be seen to update.

Then you will need to create a certificate so  you're able to install the applicaiton and you will be able to create a selfsigned certificate so you can run your application on https and which more secure. Then you will go to the bin folder and open the www file there you will update path to the certificates and private/public keys.

After that you will need use a terminal or commanline interface and go to the porject foler. Then you will need to install all the dependencies, packages, modules etc. Type npm install to install all the dependencies. 

Then you will need to type npm start to start the applicaiton. 

Or if you want to deploy it on the vm you will need to have installed all the apropaiate 
