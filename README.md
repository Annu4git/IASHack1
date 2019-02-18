# IASHack1
Application : 
Image Classification using Tensorflow based Neural Networks

Team 3-2
Anurag Chaturvedi 2018201024
Varun Gupta 2018201003
Tarpit Sahu 2018201089

Github Repo : https://github.com/Annu4git/IASHack1



Steps followed:-

1.Server Side

Train the model with the available dataset.
Command:- python run_fc_model.py

Transfer the model saved(using tensorflow saver) along with the test.sh file and restore_model.py using the run.sh.
restore_model.py consists of the code that will restore the trained model and print the accyracy for the test_data. It will also prompt for the destination ip address,username and password used while sending the output to the desried location.

test.sh – will install the docker in the client machine, will build the model and run the docker image  on the client side.

2.Client Slide:-

Run the test.sh file.	(It will install the docker in the client machine, build the docker image and run the docker image ).

The python shell will be opened. Executed the command execfile(“restore_model.py”).
This will prompt to enter the location and the name of the test dataset file. 

After this the model will run on test data and results would be generated and stored in output file.

Further, it will prompt for the destination ip address, username and password to send the output to the desired location.

After, sharing the credentials, the file named output will be shared.




