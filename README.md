# Base Application with TypeScript

This base project is to use Typescript with Lightning or, at least to create the base for create your application.

### Getting started

> Before you follow the steps below, make sure you have the
[Lightning-CLI](https://github.com/WebPlatformForEmbedded/Lightning-CLI) installed _globally_ only your system

```
npm install -g WebPlatformForEmbedded/Lightning-CLI
```

#### NPM scripts

There are several NPM scripts that will help you running the app.

`npm run test`: run the test on mocha
`npm run watch`: compile typescript and run in watch mode everything

More to come!

#### Testing

On the directory test you can put your test ;)

#### Running the App

1. Install the NPM dependencies by running `npm install`

2. Build the App using the _Lightning-CLI_ by running `lng build` inside the root of your project

3. Fire up a local webserver and open the App in a browser by running `lng serve` inside the root of your project


#### Developing the App

During development you can use the **watcher** functionality of the _Lightning-CLI_.

- use `lng watch` to automatically _rebuild_ your App whenever you make a change in the `src` or  `static` folder
- use `lng dev` to start the watcher and run a local webserver / open the App in a browser _at the same time_

#### Documentation

Use `lng docs` to open up the Lightning-SDK documentation.
