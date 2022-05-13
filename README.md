# google speech streaming socket

<p align="center">
  <img src ="https://i.imgur.com/HD07Rj9.gif" />
</p>

## Authentication
1. Visit the [Google Developers Console](https://console.developers.google.com/project)
2. Create a new project or click on an existing project.
3. Navigate to  **APIs & auth** > **APIs section** and turn on the following APIs (you may need to enable billing in order to use these services): Google Cloud Speech API
4. Navigate to **APIs & auth** >  **Credentials** and then:
  * If you want to use a new service account key, click on **Create credentials** and select **Service account key**. After the account key is created, you will be prompted to download the JSON key file that the library uses to authenticate your requests.
  * If you want to generate a new service account key for an existing service account, click on **Generate new JSON key** and download the JSON key file.

## Config
After at Authentication done getting the json file and insert At folder/file ``app.js``
``` bash
const speech = Speech({
   keyFilename: '' // insert this file json here.
});
```

## Setup websocket

``` bash
# Cd folder speech-websocket 
cd speech-websocket

# install dependencies websocket
npm install

```

## Running Project

``` bash
# run websocket 
node app

```