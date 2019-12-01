## INSTALLATION

### Tweepy: tweepy is the python client for the official Twitter API.

Install it using following pip command: 

```
pip install tweepy
```

Install Textblob using following pip command: 

```
pip install textblob
```
Also, install some NLTK corpora (bunch of texts) using following command: 

```
python -m textblob.download_corpora
```

## AUTHENTICATION

For accessing tweets using Twitter API, register an App through their twitter account. 

- Open this [link](https://apps.twitter.com/) and click the button: ‘Create New App’
- Fill the application details. You can leave the callback url field empty.
- Once the app is created, you will be redirected to the app page.
- Open the ‘Keys and Access Tokens’ tab.
- Copy ‘Consumer Key’, ‘Consumer Secret’, ‘Access token’ and ‘Access Token Secret’ and replace it in the code.
