# Phase 3 Project

## Description
This is the backend repository of the Phase 3 Project.  Here, all of the data for the Trip and Item objects is stored.

This backend uses Ruby and Sinatra to create the routes that display this data.


## Installation
To install this **entire** application, you will need to **fork and clone** these two repositories:

[Backend Repository]()

[Frontend Repository]()

Afterwards, make sure to use `bundle install` to install the gems.

## Usage
### Run Backend server
You can start your server with
```
bundle exec rake server
```
This will run your server on port [http://localhost:9292](http://localhost:9292).

### Run Frontend server
**NOTICE**: Before running the frontend server for the first time, make sure to first run
```
npm install
```
You can start the frontend server with 
```
npm start
```
This will run the server on [this port](http://localhost:3000/).

Links to the JSON data:

[Trips](http://localhost:9292/trips)

[Items](http://localhost:9292/items)

You can add a "/:id" to the end (the :id represents the ID number) in order to view the related info on an single Trip/Item.

Example: http://localhost:9292/trips/1

Which displays **only** the information of the Trip with an ID of 1, and it's Items.

## Roadmap
I currently have no plans to update this application...


## [License](LICENSE)