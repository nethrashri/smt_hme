# smt_hme


https://sci-hub.se/10.1109/JBHI.2015.2461659

https://sci-hub.se/https://doi.org/10.1007/11748625_8

MongoDB Compass on your MacBook M1. Follow the instructions below:

Install Homebrew (if not already installed):

Open the Terminal application on your MacBook.
Enter the following command and press Enter:

Copy code
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Install MongoDB using Homebrew:

In the Terminal, enter the following command and press Enter:

Copy code
brew install mongodb-community@5.0
Start MongoDB service:

Enter the following command in the Terminal to start the MongoDB service:

brew services start mongodb-community@5.0

Verify the installation:

To ensure MongoDB is running, enter the following command in the Terminal:


brew services list

You should see mongodb-community listed with a status of started.
Install MongoDB Compass:

Open your web browser and go to the MongoDB Compass download page: 
https://www.mongodb.com/try/download/compass

Choose the appropriate version for macOS.
Once the download is complete, open the downloaded file.
Drag the MongoDB Compass app to the Applications folder.
Launch MongoDB Compass:

Open the Launchpad on your MacBook.
Locate and click on the MongoDB Compass app icon to launch it.
Connect to MongoDB:

In MongoDB Compass, click on "New Connection."
By default, the connection settings should be set to localhost:27017.
Click on "Connect" to establish a connection to your locally running MongoDB instance.
That's it! You have successfully installed MongoDB and MongoDB Compass on your MacBook M1. You can now use MongoDB Compass to interact with your MongoDB databases and collections.


