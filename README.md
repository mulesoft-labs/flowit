flowit
======

Execute and share mule flows in the browser.

__How it works?__ Deploys a mule app with the provided flow in a mule instance running on CloudHub. Then try your flow by pinging an http endpoint we provide.

This is the UI project, which uses Angular, less.
The API project is [here](https://github.com/mulesoft-labs/flowit-API);

### Install

You need to install node in your machine. I recommend doing this trough nvm.

Once done, run this on install the project dependencies

```
$ npm install -g grunt-cli
$ npm install
```

### Run

Once all installed, type

```
$ grunt
```

And the web app will be hosted at [http://localhost:9001/app/#/home](http://localhost:9001/app/#/home)
