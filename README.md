dakdak-native - KAJAANISKATE.NET mobile clients
===============================================

React Native powered iOS & Android client for [KAJAANISKATE.NET](http://kajaaniskate.net). At first this app is aimed to be used for rating the images posted to the site via [kadkad-mgmt](https://github.com/miro/kadkad-mgmt), which is the current frontend of that website.

Once you have the code downloaded, follow the **[Setup guide](docs/SETUP.md)** to get started.


## Development workflow

After you have set up the project using above instructions, you can use your favorite IDE or text editor to write code, and run the application from the command line. Turn on React Native hot module reloading in the app developer menu to update your application as you code.

To learn how to structure your application and use the Redux application architecture, read the **[Architecture guide](docs/ARCHITECTURE.md)** for more details.


##### Start the application in iOS simulator
```
$ react-native run-ios
```

##### Start the application in Android simulator
(If using the stock emulator, the emulator must be running)
```
$ react-native run-android
```

##### Run unit tests
```
$ npm test
```

##### Run tests every time code changes
```
$ npm run test:watch
```


=======

## Acknowledgements
This project is a grateful recipient of the [Futurice Open Source sponsorship program](http://futurice.com/blog/sponsoring-free-time-open-source-activities). ♥


![Pepperoni - Empowered by Futurice](https://github.com/futurice/pepperoni-app-kit/blob/master/docs/pepperoni.png)

Based on *Pepperoni*, [Futurice](https://futurice.com) React Native Starter Kit
