<h1 align="center">
  <img alt="RocketShoes" title="RocketShoes" src="https://github.com/matheusleandroo/gobarber-web/blob/master/src/assets/logo-purple.svg" width="200px" />
</h1>

<h1 align="center">
  GoBarber Mobile
</h1>

<h3 align="center">
  A simple project to barber shop manager.
</h3>

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development purposes.

<h3>Prerequisites</h3>

<h4>NodeJS</h4>

You need to install NodeJS on your computer before you can use "**GoBarber Mobile**". You can install NodeJS by following <a href="https://nodejs.org/en/download/package-manager/">these instructions</a>.

Once you have completed the installation process, try typing **```npm -v```** into your command line. You should get a response with the version of NodeJS.

<h4>Yarn</h4>

Once you have NodeJs instaled, you need to install Yarn. You can install Yarn by following <a href="https://yarnpkg.com/en/docs/getting-started">these instructions</a>.

After instalition, try typing **```yarn -v```** into your command line. You should get a response with the version of Yarn.

<h4>React Native environment</h4>

You need to configure React Native environment on your computer before you can use "**GoBarber Mobile**".

If you are using Windows:

<ul>
  <li><a href="https://chocolatey.org/install">Chocolatey</a></li>
  <li><a href="https://facebook.github.io/react-native/docs/getting-started">React Native CLI</a></li>
  <li><a href="https://www.androidcentral.com/installing-android-sdk-windows-mac-and-linux-tutorial">Android SDK</a></li>
  <li><a href="https://developer.android.com/studio/install?hl=en">Android Studio</a> or <a href="https://docs.genymotion.com/desktop/3.0/01_Get_started/">Genymotion</a></li>  
</ul>

If you are using macOS:

<ul>
  <li><a href="https://docs.brew.sh/Installation">Homebrew</a></li>
  <li><a href="https://facebook.github.io/watchman/docs/install.html">Watchman</a></li>
  <li><a href="https://facebook.github.io/react-native/docs/getting-started">React Native CLI</a></li>
  <li><a href="https://docs.oracle.com/en/java/javase/13/install/overview-jdk-installation.html#GUID-8677A77F-231A-40F7-98B9-1FD0B48C346A">JDK</a></li>
  <li><a href="https://www.androidcentral.com/installing-android-sdk-windows-mac-and-linux-tutorial">Android SDK</a></li>
  <li><a href="https://developer.android.com/studio/install?hl=en">Android Studio</a> or <a href="https://docs.genymotion.com/desktop/3.0/01_Get_started/">Genymotion</a></li>
  <li><a href="https://cocoapods.org/">CocoaPods</a></li>
</ul>

If you are using Linux distributions:

<ul>
  <li><a href="https://curl.haxx.se/">cURL</a></li>
  <li><a href="https://facebook.github.io/react-native/docs/getting-started">React Native CLI</a></li>
  <li><a href="https://docs.oracle.com/en/java/javase/13/install/overview-jdk-installation.html#GUID-8677A77F-231A-40F7-98B9-1FD0B48C346A">JDK</a></li>
  <li><a href="https://www.androidcentral.com/installing-android-sdk-windows-mac-and-linux-tutorial">Android SDK</a></li>
  <li><a href="https://developer.android.com/studio/install?hl=en">Android Studio</a> or <a href="https://docs.genymotion.com/desktop/3.0/01_Get_started/">Genymotion</a></li>
</ul>

<h4>API</h4>

You must have the <a href="https://github.com/matheusleandroo/gobarber-api">GoBarber API</a>.

## Deploy

After clone repository, go to folder and follow this steps:

<h4>macOS</h4>

- Run **`yarn`** to install dependencies;
- Run **`cd ios`** and **`pod install`**;
- Run **`cd ..`** and **`react-native run-ios`** to start de aplication.

To run Android App, open the simulator (Android Studio or Genymotion) and run **`react-native run-android`**.

<h4>Windows or Linux distributions</h4>

- Run **`yarn`** to install dependencies;
- Open the simulator and run **`react-native run-android`** to start de aplication.

If the application do not start, run **`react-native start`**.

**Possible errors:**

- No bundle URL present: run **`rm -rf ios/build/; kill $(lsof -t -i:8081); react-native run-ios`**
- spawnSync ./gradlew EACCES: run **`chmod 755 android/gradlew`**

Now you can use "**GoBarber Mobile**".

## Built With

<ul>
  <li>React Native</li>
  <li>Redux</li>
  <li>Redux Saga</li>
  <li>Axios</li>
  <li>PropTypes</li>
  <li>Vector Icons</li>
  <li>Styled Components</li>
  <li>ESLint + Prettier + EditorConfig</li>
</ul>

## Authors

<ul>
  <li><a href="http://matheusleandro.com">Matheus Leandro</a></li>
</ul>

## License

This project is licensed under the MIT License - see the <a href="https://github.com/matheusleandroo/rocketshoes-mobile/blob/master/LICENSE">LICENSE.md</a> file for details.

Based on <a href="https://rocketseat.com.br/bootcamp">Rocketseat Bootcamp</a> :rocket:

