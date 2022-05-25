# Instant Messaging Application

Developed a web-based application based on Redis publish-subscribe mechanism together with ReactJS, NodeJS and socket programming to enable instant messaging between users and deployed it using Kubernetes.


## Running the dev environment:

There are a total of 3 processes. 

Terminal 1
```
yarn install
yarn startboth
```

Terminal 2
```
cd chat-server
python3 app.py
```

Terminal 3
```
cd analyzer
python3 analyzer.py
```
