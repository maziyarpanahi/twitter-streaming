# twitter-streaming
## Store Tweets from Twitter Public Streaming API into NoSQL databases
**NOTE**: This repo is only for teaching purposes only :)

### Node.js and NPM
First let's install NVM:
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
source ~/.bashrc
```
or
```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
source ~/.bashrc
```
Second, install the latest Node.js and NPM via NVM:
```
nvm i v8
nvm alias default v8.
npm install -g npm
```

NOTE: run this if you already have Node.js installed
```
nvm i v8 --reinstall-packages-from=default
nvm alias default v8.
npm install -g npm
```

Let's check if the Node.js and NPM have been installed correctly:

```
node -v
npm -v
```

Last, run this command to install dependencies:
```
npm i
```
### Setup Twitter Application
1. Please create an account from here:

[Twitter Apps](https://apps.twitter.com/)

2. Complete the `TwitterAuth.js` file inside `conf` directory accordingly. 

### Start the app
```
npm start
```

