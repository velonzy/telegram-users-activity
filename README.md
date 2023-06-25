# telegram-users-activity
## About the application
The application parses the messages of the chat you have chosen and saves the number of written comments and reactions.
## Creating a client
To run the application, you need to get your personal api_id and api_hash from https://my.telegram.org/. And write these values ​​to the file *config.ini*.

Example:
```
[Telegram]
api_id = 12345
api_hash = 0123456789abcdef0123456789abcdef
```
After runnig the code, you have to enter your phone number country code but without '+' symbol:

Example:
```
Please enter your phone (or bot token): 79179009090
Please enter the code you received: 12345
Signed in successfully as Username
```
Next, a list of chats appears. To see the statistics of your channel, you must have comments enabled.
Data will be saved at **/csv files** directory
