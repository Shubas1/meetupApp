#####README:

In this application, front-end code is an ember application which is the client facing web app and code for this application is present inside ember folder.

Backend for this application is done using Rails, which have some restfull APi's writtent

Front-end calls the backend restfull API services and displays on page


## Start the Baceknd

1 -  Go inside rails folder

2 - run bundle install

3 - run rake db:create

4 - rake db:migrate

5 - rake db:seed

5 -  start the server using - `rails s` command, then server will be running at locahost:3000 URL


##Start front end code

1 -  Go inside ember folder and run npm install (make ember is installed on your system using , npm install -g ember-cli)

2 - Start the server using below command

ember server --proxy http://localhost:3000

This command will start the server at 4200 PORT and will proxy all API calls through localhost:3000 server, where our backend code is running


