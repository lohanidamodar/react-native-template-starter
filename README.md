This is personal app setup that I use for my RN projects.

This is WIP, as I need to init and grow more than one project using this.

$`react-native init --template starter <new project name>`

### Things to do after init

1. Run `node scripts/postInit.js` It will:
  - Install dev dependencies
  - Replace appKey in index files
2. Finish splash screen installation [as instructed](https://github.com/crazycodeboy/react-native-splash-screen#third-stepplugin-configuration)
3. Examine `.env` files for react-native-config
4. Run new app

### Things included
- [Reactotron](https://github.com/infinitered/reactotron#documentation) for development
- [Redux](http://redux.js.org/) with [redux-persist](https://github.com/rt2zz/redux-persist#redux-persist) and [redux-saga](https://redux-saga.github.io/redux-saga/index.html)
- [react-native-splash-screen](https://github.com/crazycodeboy/react-native-splash-screen#react-native-splash-screen)
- [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)
- [react-navigation](https://reactnavigation.org/docs/intro/) with some basic routing via redux
