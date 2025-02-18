# Chitter Challenge

## Task
Write a small Twitter clone that will allow the users to post messages to a public stream.

## Download and Run instructions
```
git clone https://github.com/michelle-watkins/chitter-challenge-apprenticeships.git
bundle 
rackup
```
Open localhost in your browser with the specified port (found in your terminal message once you've ran `rackup`).

## Setting up the databse
1. Connect to `psql`
2. Create the database using the `psql` command `CREATE DATABASE chitter;`
3. Connect to the database using the `pqsl` command `\c chitter;`
4. Run the query saved in the file `01_create_messages_table.sql`

## Test Database Setup
* Connect to `psql`
* Create the database using the psql command `CREATE DATABASE chitter_test;`
* Run the query we have saved in the file `01_create_messages_table.sql`
* Run `\l` to list the databases, you'll see two databases for this application: `chitter`, and the new `chitter_test` database.

## User Stories
```
As a Maker
So that I can see what people are doing
I want to see all the messages (peeps)
in a browser
```

## Domain Model
See chitter.pdf on GitHub.
