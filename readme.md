# cats_vs_dogs
Prediction between cats and dogs using CNN architecture


Below files are mandatory to put the code in production in Heroku:

1) runtime -> It defines the run time evinronment and so python version to be used needs to be mentioned
2) Procfile -> It defines the entry point of the application, by default the server which is always available in Heroku is always gunicorn.

   app:app represents "file:classname"