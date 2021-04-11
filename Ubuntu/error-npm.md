```
npm ERR! code EAI_AGAIN
npm ERR! errno EAI_AGAIN
npm ERR! request to https://registry.npmjs.org/cordova failed, reason: getaddrinfo EAI_AGAIN registry.npmjs.org:443

npm ERR! code EAI_AGAIN
npm ERR! errno EAI_AGAIN
npm ERR! request to https://registry.npmjs.org/cordova failed, reason: getaddrinfo EAI_AGAIN registry.npmjs.org:443
```

Update your npm version.

sudo npm cache clean -f
sudo npm install -g n
sudo n stable
npm -v it should print 6.4.0.
Alternatively you ca just type sudo npm install npm@latest -g in terminal
