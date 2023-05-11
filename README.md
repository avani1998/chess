# Chess - Visualization and Insights
Big Data Project for CS-GY 6513

Please download the database used for this project from <br>
[Download](https://drive.google.com/file/d/1F8QWIkjhrOJdqkNrlN19nnWQpeww-2mv/view?usp=sharing)

Make sure mongoDB is connected on localhost on port number 27017

The project consits of five files which run everything.
1. main.ipynb: To initialize the mongoDB from the database
2. apiData.ipynb: To initialize the mongoDB from APIs
3. publishAPI.ipynb: To publish the APIs derived out of the project
4. scheduler.ipynb: To automatically add new players and matched at the end of every month
5. flask.ipynb: To demo a light weight web app and user interactive frontend

To initialize the mongoDB database, you will need to run main.ipynb. This file will populate the mongoDB using the database downloaded from the drive above.
Then you can run apiData.ipynb to populate mongoDB from APIs of chess.com. And finally you can run publishAPI.ipynb if you want to publish the dervied APIs.
For demo purposes, the files main and apiData a MAX_NUMBER_OF_PLAYERS counter in each files which limits the number of players that can be added to mongoDB.
To add all the data, you can make MAX_NUMBER_OF_PLAYERS == -1. However, this will take a lot of time to execute.
Once all that is done, you can go ahead and run the flask.ipynb file. This file will host a web app on the localhost on port 5001.

You can run scheduler.ipynb in the background indefinitely.
