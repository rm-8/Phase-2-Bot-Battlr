Bot Battlr

Welcome to Bot Battlr, the ultimate destination for building your own Bot Army!


Introduction
Bot Battlr is a React application designed to allow users to browse through a list of robots, view details of each robot, and enlist robots into their army. This project focuses on practicing components, props, state, events, and data fetching in React.

Project Setup
To set up the project, follow these steps:

Create a new project folder.
Create a new GitHub repository. Make sure it is private and add your team member as a contributor.
Create a db.json file in your project directory to serve as your local JSON DB server.
Run the following command to start the backend JSON server:

json-server --watch db.json
Test your server by visiting the route http://localhost:8001/bots in your browser.
Project Guidelines
Your project should adhere to the following guidelines:

Core Deliverables
As a user, you should be able to:

See profiles of all bots rendered in BotCollection.
Add an individual bot to your army by clicking on it. The selected bot should render in the YourBotArmy component. The bot can only be enlisted once. The bot does not disappear from the BotCollection.
Release a bot from your army by clicking on it. The bot disappears from the YourBotArmy component.
Discharge a bot from your service forever by clicking the red "x" button, which deletes the bot both from the backend and from the YourBotArmy on the frontend.
Technologies Used
React
JSON Server
JavaScript
HTML
CSS
Contributing
Contributions to Bot Battlr are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.