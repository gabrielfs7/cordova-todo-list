# cordova-todo-list

A mobile todo list app built using Apache Cordova

# Requirements

1. Install brew
2. Install cordoba
3. Install nodejs and npm
4. Install Android SDK
 - brew install android-sdk

1. Creating the Project:
 - cordova create cordova-todo-list cordova.todo.list TodoList
 - cd cordova-todo-list
2. Adding platform support
 - cordova platform add android
 - cordova platform add ios
3. Check current platforms
 - cordova platforms ls
4. Build the android and IOS Apps:
 - cordova build ios
 - cordova prepare ios
 - cordova compile ios
 - cordova build android
 - cordova prepare android
 - cordova compile android
5. Emulate de aplication
 - cordova emulate android
6. Run application
 - cordova run android
