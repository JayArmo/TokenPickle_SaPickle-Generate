# TELEGRAM
[🧑‍💻 Owner](https://telegram.me/JayArmo)

[📢 Update Channel](https://telegram.me/Jay_Bots)

[♻️ Suppot Group](https://telegram.me/Jay_Bots_Discussion)

# How To Generate token_sa.pickle & token.pickle File 🗃️  With Android Easily After Google Auth2.0 New policy update. Without any kind of error.
### 1. Install Termux [F-Droid](https://f-droid.org/en/packages/com.termux/)
### 2. Open Termux and just copy paste all the commands that described below, Make sure you have internet connection. if you see Y/n then Type y.
```
apt update && apt upgrade && pkg i git && pkg i python3 && pkg update python && pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib && pip install --upgrade pip
```
### OR
```
sudo apt update && sudo apt upgrade && clear
```

```
pkg install python3
```

```
pkg install git
```

```
pip install --upgrade pip
```

```
pip3 install -r requirements-cli.txt
```

### 3.
```
git clone https://github.com/JayArmo/TokenPickle_SaPickle-Generate
```
### 4. make sure Credentials.json file present in your storage folder not in Sd card. if not then just move credentials.json file into the sdcard. Not in any folder.
### 5. you have to give storage permission to termux. for that use this command.
```
termux-setup-storage
```
### 6. 
```
cd /sdcard
```
### 7. 
```
cp -r credentials.json /data/data/com.termux/files/home/TokenPickle
```
### 8. Just exit from termux and reopen it.
### 9.
```
cd TokenPickle
```
### 10. e Gnerate token_sa.pickle file 
Note - AUTHORIZE URL
```
python3 gen_sa_accounts.py
```
### 11. Gnerate token.pickle file 
Note - AUTHORIZE URL
```
python3 GenerateTokenPickle.py
```
### 12. You'll find a url https://accounts.google.com/o/oauth2/=offline like this. just copy this url and paste on browser and login into your google account. that's it. you'll see 'The authentication flow has completed. You may close this window' this massage. then you're done.
### 12. 
```
cp -r token.pickle /sdcard
```
### 14. Boom 💥! 
goto your sdcard (phone memory) you'll find token.pickle there.

We're Done.
# Enjoy And don't forget to star this repo 🙂

# Credits...
[`JayArmo`](https://github.com/JayArmo)
