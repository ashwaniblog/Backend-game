# Blackjack Backend
## Setup

The backend and frontend are bundled as different endpoints. The backend is a Node [socket.io](http://socket.io/) server and runs on port *3000*. The frontend is served from a different Express server on port *8000*. Included in the repository are all the development scripts. Switching to different ports requires changing configuration on both ends.

### Prerequisites

1. Install Node.js and npm (http://nodejs.org/).
2. Install bower and gulp:
	
	`npm install -g bower`

	`npm install -g gulp`

### Setting up the Backend

1. Change directory to `blackjack-backend`
2. Install required packages:

	`npm install`

3. If all successful, start the server:

	`npm start`

