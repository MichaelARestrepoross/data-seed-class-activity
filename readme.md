# Data Seed Class Activity

<img src="digital.png" height="500" width="500">

You are going to seed your JSON Server with data that you would be able to consume in a frontend application.

## Getting Started

1. `fork` and `clone` this repository
2. `npm install`
3. `npm run dev` and your server should run on localhost 50001

## Choose a Subject

Select a Subject of your choosing for Your data.

Here a some ideas:

- Choose one of the following subjects for your data set:
- E-Commerce Product Catalog
- Social Media Posts
- Event Management
- Educational Course Directory
- Real Estate Listings
- Restaurant Menu and Orders
- Travel and Tourism
- Healthcare Patient Management
- Library Management System
- Employee Directory
- Vehicle Rental Service
- Fitness and Workout Tracker
- Movie Database
- Weather Forecast Information
- Banking and Finance

## Create Your Data

Your data should include an array of objects that will be nested in the curly braces in the `.json` file.

Each object in the array should contain:

- an id with the data type of string
- a key with a value data type of array
- a key with a value data type of object
- a key that is a string
- any other keys of your choosing

Possible ways of creating data are:

1. Generate data using ChatGPT.
1. Create data using Mockaroo.
1. Hand-code the data.
1. Make a get call to a third party api, grab the data and place it in this server

If you have another option for generating data you are welcome to use that.

## Update the JSON Server

Add your created data to `db.json` and `originalData.json`

1. Assign a unique key to your data set. For example:

```json
{
  "yourDataKey": [...your data...]
}
```

2. Backup Original Data

Also, add your data to the originalData.json file. This step is crucial for resetting the data later if needed.

## Deployment

Deploy your server on render.com and test in either the Browser or Postman using the `localhost:5001/api/<your json key name>` endpoint.

## Completion

Make a pull request to this parent repo with your repo results
