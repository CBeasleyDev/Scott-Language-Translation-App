# Scott-Language-Translation-App
Scott is a straightforward language translation app that allows users to easily translate text between languages through a user-friendly GUI. Users can input text, translate it into a chosen target language, and dynamically change the target language as needed.


Features
Translation: Users can input text for translation, and the app will provide the translated text based on the selected source and target languages.

Change Target Language: Users can dynamically change the target language for translation by clicking the "Change Target Language" button.

Getting Started
Prerequisites
Python 3.x
googletrans library: Install using pip install googletrans==4.0.0-rc1
gtts library (optional, for text-to-speech functionality): Install using pip install gtts
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your_username/scott-language-app.git
cd scott-language-app
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Run the app:

bash
Copy code
python scott_app.py
The app GUI will appear. Enter the text you want to translate, select the target language, and click the "Translate" button.

To change the target language, click the "Change Target Language" button and enter the new language code when prompted.

Dependencies
googletrans: Python wrapper for Google Translate API.
gtts: Google Text-to-Speech library (optional, for text-to-speech functionality).
Contributing
If you'd like to contribute to the project, feel free to fork the repository and submit a pull request. Contributions are welcome!

License
This project is licensed under the MIT License.
