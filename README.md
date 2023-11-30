## Run Locally

Clone the project

```bash
  git clone https://github.com/adamwisnup/modul4-cyberacademy.git
```

Go to the project directory

```bash
  cd modul4-cyberacademy
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm start
```

Go to browser

```bash
  localhost:8000
```

## Usage

Pada folder /public/script.js ubahlah api_url sesui dengan Channel ID dan Read API Keys pada Thingspeak

```javascript
const api_url =
  "https://api.thingspeak.com/channels/<ChannelID>/feeds.json?api_key=<ReadAPIKeys>&results=1";
```

tanpa menggunakan {}

## Upload to your repository

Before upload file to your repository in github, delete folder '.git' first, and do 'git init' for create your commit
