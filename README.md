# Starting

`expo init WhatsApp`

Choice typescript with tabs

`yarn start android`

So let's code...

## Preparing navigation

This project use `react-navigation` so install...

`yarn add @react-navigation/material-top-tabs react-native-tab-view react-native-reanimated`

and because icons is a dependency maybe you need run

`yarn install`

## Some points to be careful

This project use the version of `navigation` `>=5.8`. Maybe in lot of examples you will find configuration of styles, title and other things in the `index.tsx` of navigation but now each tab needs have your configuration and I setup this using directly in `MainTabNavigator.tsx`

Using top-navigator maybe you will need run `yarn add react-native-pager-view`. I had this problem...

