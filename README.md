# Social-Network-API

An API for a social network web application in which users share their thoughts, are able to react to friend's thoughts, and create a friend list.

# Description 

This is an API for a social network that utilises a MongoDB database to handle large amounts of unstructured data, Express.js for routing, Mongoose ODM, and the moment package to format time stamps.

# What does this project do? and how?

The following installation was required:

Download the repo files from the link below
You must have mongoDB installed

Run the following at the command line
    - npm init -y
    - npm install express
    - npm install mongoose
    - npm install moment
   
Start the server
    $ npm start

Open Insomnia Core to test API routes

## User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database

WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database

WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

# So far what has been achieved and further improvements?

All requirements above has been achieved.

# To access Github Repository 

1. https://github.com/samira0101/Social-Network-API.git

# To access video 

## Presentation [Video]
User route - https://drive.google.com/file/d/1sgr7MhwqxqRsM4OLRpkwyg6RcDzeuFGG/view

Friend route - https://drive.google.com/file/d/1kVk5WP0MpAKx0ai5b6PuR_mVrNx5obp-/view

Thought route - https://drive.google.com/file/d/1IdaeyFQrWgMCABzv0cdUxzzT079IPgAC/view

Reaction route - https://drive.google.com/file/d/1Aa2w5u1P-czWuOzU6Rf1MsnQU-uQESaI/view

# References

1. https://birmingham.bootcampcontent.com/university-of-birmingham/UBHM-VIRT-FSF-PT-11-2021-U-LOL
2. https://mongoosejs.com/docs/tutorials/virtuals.html
3. https://codesource.io/how-to-use-mongoose-virtual-property/
4. https://expressjs.com/
5. https://www.mongodb.com/docs/manual/reference/operator/aggregation/count-accumulator/#mongodb-group-grp.-count
6. https://www.section.io/engineering-education/group-operator-in-mongodb/
7. https://www.guru99.com/node-js-mongodb.html
8. https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/mongoose
9. https://www.npmjs.com
10.https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide