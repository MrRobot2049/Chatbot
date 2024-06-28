Project title - "Cheeku the chatbot"
Description: It is a chatbot designed to provied the user meanings, synonyms of words and translations of phrases.

Installation
This project requires the Google Cloud SDK. Please follow the instructions below to install it:

```sh
curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-391.0.0-linux-x86_64.tar.gz
tar -zxvf google-cloud-sdk-391.0.0-linux-x86_64.tar.gz
./google-cloud-sdk/install.sh

Usage
I recommend once looking through rasa documentation. It will provide you with an understanding of how the project works.For usinh the chatbot you can go through the following steps:
Run the following commands in two separate terminal windows;
-rasa run --cors "*"
-rasa run actions
Then open the html file linked to the project. Chatbot will be up and running in the default web browser.


Contributions
If you are open to contributions, I would suggest the following
-Train more data in nlu.yml
-Integrate text to speech google api so that pronunciation of words can be done
-There is a scope of improvement in frontend development of website

