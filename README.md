# National Voting System

This is an in-depth software engineering project from my academic days at the University of Iowa. It was an Agile simulation project that took place over the course of one semester (five months). We used a Hybrid Agile-Scrum approach to capitalize on the incremental client requirements and four person team size. The tech stack used was Python Flask with MySQL.

## Features

The National Voting System is a project that implements an electronic solution to how we vote on our next government officials in the United States. Anyone can sign up with their precinct and userdata is stored on the database. They can log-in then vote in any elections that include their precinct and recover their account if a password is lost. Admins can create elections, assign polling managers, approve user profile requests, design ballots, and manage user profiles with a CRUD interface for filtering and managing users' data. Polling Managers can activate/deactivate ballots and declare elections when they're finished. Voters remain anonymous while still ensuring the integrity of the results. Finally, anyone can sort and view the elections' results.

In-depth documentation of these use-cases can be found [here](https://docs.google.com/document/d/1897FEuNxtdLff7yNNg8_e8hOGvkVeFZlAR4CcyCPXDE/edit?usp=sharing).

## Screenshots



## How to Run

Open the project in your favorite IDE. Make sure you have the latest version of Python with PIP installed.

Then run the following series of commands in the terminal to create a virtual environment and download the necessary packages.

```
py -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

Then boot up MySQL Workbench and start a new server under root with the project name of "project" on port 3306. Remember your password.

Navigate to Server > Data Import. Tick the "Import from Self-Contained File" radio button and change the file to 

The initial DB is located in the MySQL folder and named DatabaseV1Team1.sql, to use this you will need to download it and then import it to your local MySQL Workbench environment.
