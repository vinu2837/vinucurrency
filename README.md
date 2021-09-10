
### What's inside this repo?

1. Endpoints to create alerts,to fetch all the active alerts, and to get the current market price.
2. Job schedulers to remove the expired alerts automatically.
3. Process alerts using BullMQ
4. Send email notifications

For a more detailed explanation of the code, you can refer to my article posted on the Medium associated with this project.

### Built With

- [Node.js]() - JavaScript runtime built on Chrome's V8 JavaScript engine.
- [Express.js]() - Minimal and flexible Node.js web application framework
- [BullMQ]() - BullMQ is a Node.js library that implements a fast and robust queue system built on top of Redis.

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps :

### Prerequisites

To run this project, you'll need to have the following installed:

- Node.js : [https://nodejs.org](https://nodejs.org)

- npm :
  ```sh
  npm install npm@latest -g
  ```
- Redis server : [https://redis.io/](https://redis.io/) <br>

> You can also use Redis server cloud service if you prefer.
> <br>

### Installation

1. Register at [SendGrid](https://sendgrid.com) and create an API KEY.

2. Clone the repo :
   ```sh
   git clone https://github.com/vinu2837/vinucurrency.git
   ```
3. Install dependencies (use `sudo` if required) :

   ```sh
   npm install
   ```

4. Update project settings in the config.js file.
5. Start the server :
   ```sh
   npm start
   ```
