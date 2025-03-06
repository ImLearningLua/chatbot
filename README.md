TO make this work please install using a Virtual machine.

and use
 pip install pyTelegramBotAPI
pip install tensorflow
pip install nltk




    Clone the repository.
    Install the required dependencies.
    Uncomment nltk.download('punkt') and nltk.download('wordnet') in training.py
    Run main.py.



Code Structure

    main.py: This is the main script that runs the chatbot. It includes the logic for handling user queries, presenting menus, and managing orders.
    intents.json: This file contains predefined patterns and responses for the chatbot.
    menu.json: This file contains the menu items that the chatbot can present to the user.
    words.pkl and labels.pkl: These files are used for processing user queries.
    chatbot_model.h5: This is the trained model that the chatbot uses to understand user queries.




Note

This bot uses the Telebot library and requires a valid Telegram bot token to function. Please replace the placeholder token in the main.py file with your own token.

bot = telebot.TeleBot('YOUR_TELEGRAM_BOT_TOKEN')



xample Use

This is a regular use case of using Kayo to order a food.

Example Screenshot For some reason doesn't work in a read me :(



AND!

 Contribution
Feel free to fork this repository, make changes, and submit pull requests. If you find any bugs or have any suggestions, please open an issue.


This project is licensed under the MIT License.
