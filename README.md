# Phonebook full-stack

## Link to online application

https://arcane-reaches-66730.herokuapp.com/

## Repository structure

The "frontend" folder contains the React app for the phonebook.
The "backend" folder contains the Node server. 
The folder "arcane-reaches-66730" contains the Git repository deployed to Heroku.

## Set up to run locally

1. Define ```PORT``` and ```MONGODB_URI``` environment variables.
2. Enter ```npm install``` in the front-end and back-end folder.
3. Enter ```npm run copyfull``` from the backend folder.
4. Enter ```npm start``` from the to_deploy folder.
5. Go to ```http://localhost:your_chosen_port/```.

## CI/CD scripts

The following commands should be executed from the backend folder.

- To generate a production build of the front-end and copy it to the deployment folder
  - ```npm run copyfront```

- To copy the backend folder to the to_deploy folder
  - ```npm run copyback``` 

- To execute the above two commands at once
  - ```npm run copyfull```

- To add untracked files to the to_deploy folder and commit them
  - ```npm run deploy "your message here"```

- To deploy most recent commit to Heroku
  - ```npm run deploy```

- To copy the backend and frontend, add and commit all files and then deploy
  - ```npm run deployfull "your message here"``` 

You must initialise a Heroku repository in the to_deploy folder before running the last two commands. 
