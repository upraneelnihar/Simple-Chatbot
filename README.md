# Simple-Chatbot

- This repository consists the python code for developing a simple chatbot.
- For demomstration the chatbot is configured for performing two tasks:
    - `Movie Search`
    - `Restaurant Search`

# Data Description:
- The `db` folder contains the data files :
    - `movies.csv`: Contains list of movies data in the below format.
       ```
       [Movie, language, Actor, Theatre_Name, genre, date, Show_Time, location]
       ```
    - `restaurants.csv`: conatins list of restaurants data in the below format.
       ```
       [cuisine, costtype, location, Restaurant]
       ```
- The `entities` folder contains the data for various entities present in each task:
    - `Movie search`:
    ```
    [Actors, genre, date, language, location]

    ```
    - `Restaurant Search`:
    ```
    [cuisine, costtype], location]
    ```
- The `intents` folder contains the data for possible user input for each intent.
- The `params` folder contains the dialog flow  to capture the required params for each intent.
