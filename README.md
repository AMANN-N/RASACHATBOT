# RASACHATBOT
The Project contains simple Chatbot which works on RASA Framework. The Chatbot can also be hosted on a local server using Django.
To add your own data(question answers) to the chatbot one only needs to change the following files.

1. domain.yml
2. nlu.yml
3. stories.yml

-Create a project_directory for your project
-initialize RASA within your project_directory by running command rasa init
-Replace the files in the project_directory with the ones from downloaded template
-Evaluate the bot in terminal with command rasa test.
-OPTIONAL: If you find a file called actions.py in your template directory, run this command in a new terminal rasa run actions.

  - type " rasa run -m models --enable-api --cors "*" --debug" to setup the local server.
  - type " python .\manage.py runserver" (runs the server)
  - rasa train ( trains the bot)
 
-Start talking to the bot in terminal with command rasa shell
