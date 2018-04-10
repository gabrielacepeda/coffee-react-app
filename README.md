# Coffee-React-Oauth app
This coffee app uses local authentication and Node.js middleware.

![coffee preview](https://github.com/gabrielacepeda/coffee-auth/blob/master/coffee.png)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, React, Node.js middleware (Express, Passport, Mongoose)

I installed the necessary middleware that would be needed to initialize this app. The local authentication service was delivered by passport, which allows the implementing of authentication. The way it works is the Barista logs into their account and adds a customer's coffee order to a list. Once the order is prepared, the coffee is marked as complete, and the name of the barista and "complete!" will appear next to the order.
                                                                         

## Optimizations
When the coffee order is marked as completed, the name of the customer and his/her order could be announced via a text-to-voice API. 

## Lessons Learned:
It was my first applcation using React and it was challenging at first, but I learned a lot.


## Installation

1. Clone repo
2. run `npm install`

## Usage

1. run `node server.js`
2. Navigate to `localhost:8080`

## Credit

Modified from Scotch.io's auth tutorial
## coffee

