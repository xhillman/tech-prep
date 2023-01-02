# TechPrep

An Alexa Skill that helps users prepare for technical interviews, including code challenges and behavioral interview questions.

**Authors:**

- Xavier Hillman
- Stephen Clemmer
- KC Hofstetter
- Brandon Pitts
- Jack Stubblefield

## Features

- Technical code challenges
- Behavioral interview questions
- Get a hint for the code challenge
- Repeat the code challenge
- Send the code challenge solution to your email
- Ask for recent developer jobs
- Have recent jobs sent to your email

**Examples:**

1. Code challenges:

- User asks: 'Hey Alexa, give me a code challenge'
- Alexa talks back and gives a challenge i.e.,  “Write a function that traverses a binary tree and console logs each value”

2. Behavioral interview questions:

- User asks: "Hey Alexa, ask me an interview question"
- Alexa talks back and gives a question i.e., “Tell me about a time you had to work with a difficult team member”

3. Get recent jobs:

  - User asks: "Hey Alexa, what are the most recent developer jobs?"
  - Alexa talks back and gives a list of jobs i.e., “Here are the most recent developer jobs: 1. Software Engineer at Amazon, 2. Software Engineer at Microsoft, 3. Software Engineer at Google”

**Technologies Used:**

- Alexa Skills Kit (ASK) SDK
- AWS Lambda
- AWS S3 Storage Bucket
- AWS SES (Simple Email Service)
- Axios for API calls

**Required package.json dependencies:**

        "dependencies": {
            "ask-sdk-core": "^2.7.0",
            "ask-sdk-model": "^1.19.0",
            "aws-sdk": "^2.326.0",
            "@aws-sdk/client-s3": "3.190.0",
            "node-fetch": "2.6.7"
          }

### UML

![Tech Prep UML](./img/Tech-Prep%20UML%20(1).png)

### For more information on the features of this Alexa Skill, please see the following:

[Developer README Table of Contents](./READMEs/Table-of-Contents.md)
