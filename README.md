# STREAMY

## Overview

- Final project for [Modern React with Redux](https://www.udemy.com/react-redux/learn/v4/content)
- The project is a React/Redux based live streaming platform. Authenticated users are able to create their own stream and live broadcast their computer screen to browser by using Open Broadcaster Software(OBS).

<img src='https://github.com/yiiifan/Streamy_server/blob/master/img/streamy.png?raw=true' width= '500px'>

<img src='https://github.com/yiiifan/Streamy_server/blob/master/img/streamy_display.png?raw=true' width= '500px'>

## Dependency

- axios: 0.19.0
- flv.js: 1.5.0
- lodash: 4.17.15
- react: 16.8.6
- react-dom: 16.8.6
- react-redux: 7.1.0
- react-scripts: 3.0.1
- redux: 4.0.4
- redux-form: 8.1.0
- redux-thunk: 2.3.0

- json-server: 0.15.0
- node-media-server: 2.1.2

## Ussage

### Structure

1. Streamy_server contains all server part files
2. Streamy_client is React&Redux based web app created by create-react-app
3. To setup, move all files from Stream_client to Stream_server/client

### Setup your stream

1. Signed in with Google OAuth
2. Create a new stream

3. Get your stream id
4. Open OBS and setting
   1. Stream Type : Custom
   2. URL: rtmp://localhost/live
   3. Stream Key: id

## Future Improvement

1. Add up comment and user profile
2. Upload data to cloud
3. Improve UI
