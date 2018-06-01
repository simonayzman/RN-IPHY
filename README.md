# RN-IPHY

![](./app-demo.gif)

_This project was bootstrapped with [Create React Native App](https://github.com/react-community/create-react-native-app). Below you'll find information about performing common tasks. The most recent version of this guide is available [here](https://github.com/react-community/create-react-native-app/blob/master/react-native-scripts/template/README.md)._

## Quick Start

RN-IPHY is a React Native demo application featuring a feed of gifs (supplied by Giphy) that explores some of the platform's available functionality. For more guidance, information, and links, check out [the sister presentation for this repo](https://docs.google.com/presentation/d/1VfOOCfF9K4qcX-X_JT_YsUNoI-FHeB9B75dnZgt6WOU/edit?usp=sharing). You can follow along the gradual buildup of code by checking out the code in stages. First, install the Expo app on your smartphone. Then, start by running the following commands in your terminal:

```
$ yarn install
$ git checkout stage0
```

In a separate tab, start up the javascript bundle server and keep it running:

```
$ yarn start
```

Follow the Expo instructions for viewing your app. Whenever you want to progress forward, simply check out the next stage. For example: 

```
// Currently on the stage5 commit
$ git checkout stage6
```

## Demo Progression

### start/stage0 to stage1
* Added an extra line of text to the screen!

### stage1 to stage2
* Created a simple HomeFeed stub component

### stage2 to stage3
* Added a list of stub “cells” representing gifs

### stage3 to stage4
* Added helpers and created directory structure
* Added header, footer, and multiple columns

### stage4 to stage5
* Add giphy API client to app
* Added fetch related state to HomeFeed

### stage5 to stage6
* Refactored gif list into separate component

### stage6 to stage7
* Added data & limit props to GifList

#### stage7 to stage8
* Added React Native gifs toggle to HomeFeed

### stage8 to stage9
* Added new app images
* Updated gif list layout and individual gif styling
* Added automatic layout animations

### stage9 to stage10/finish
* Added sharing functionality on gif tap
