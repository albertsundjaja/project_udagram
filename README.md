# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

## Setup Node Environment

You'll need to create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`

## The URL to access the service

this project is hosted on AWS Elastic Beanstalk, note that if it's not accessible that means it has been shut down due to cost constraint ;)

```
http://project-udagram-dev.us-west-2.elasticbeanstalk.com/
```

### Example request

**NOTE** the image_url below is not actually valid, and it will give an error. Please replace with your own url

```
http://project-udagram-dev.us-west-2.elasticbeanstalk.com/filteredimage?image_url=https://theurlforyourimage/kitten.jpg
```