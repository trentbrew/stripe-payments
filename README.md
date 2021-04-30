## Fullstack Stripe Payments for the JavaScript Developer

## Frontend Setup

The backend API can be integrated with the following frontend frameworks. 

### Vue

```
cd vue-app
npm install
npm run serve
```

## Deployment

### Option 1 - Docker

Dockerize the server for deployment to services like Cloud Run, GKE, Elastic Beanstalk, etc. 

```
cd server
docker build -t fireship/stripe-server .
docker run -p 3333:3333 fireship/stripe-server 
```

### Option 2 - Firebase Cloud Functions

Deploy to Cloud Functions to simplify your code with a tight integration to Firebase. 

```
firebase deploy --only functions
```
