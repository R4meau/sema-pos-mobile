# SEMA POS Mobile

SEMA POS is a React Native Android client that allows SWE kiosk supervisors to process sales and water quality data, manage customer data, do basic analyses and operations.

It's offline-first and sends data through the SEMA Core REST API.

---

## Screenshots

TBD

## Requirements

For development, you will need Node.js, <a href="https://facebook.github.io/react-native/docs/getting-started" target="_blank">React Native</a> and a node global package manager, Yarn, installed in your environement.

You will also need to make sure SEMA Core is setup and running successfully on your development machine.

## Basic Usage

- Clone the repo and enter the project folder
```
git clone https://github.com/untapped-inc/sema-pos-mobile
cd sema-pos-mobile
```
- Install dependencies:
```
yarn
```
- Make sure you have an Android emulator running (i.e.: GenyMotion)
- Run the client:
```
react-native run-android
```

It should start running on your emulator.

## Contributing

Please, read our [Contribution Guidelines](https://github.com/untapped-inc/sema-pos-mobile/blob/master/CONTRIBUTING.md) if you wish to participate into the development of SEMA.

## Building for Production

For the full documentation on how to build/run this project in production mode, please, follow the tutorial [over there](https://untapped-inc.github.io/sema-docs/deploying-to-production/).
