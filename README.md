# react-native-template

# After Cloning
- npm install
- cd ios && pods install && cd ..
- npx react-native run-ios && npx react-native start

# No Bundle URL Error
1. Deleted: ios/main.jsbundle
2. Run comment: react-native bundle --entry-file index.js --platform ios --dev false --bundle-output ios/main.jsbundle --assets-dest ios

# React Native Elements
1. yarn add react-native-elements
2. yarn add react-native-vector-icons
3. react-native link react-native-vector-icons
