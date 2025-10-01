Test app to demonstrate reproduction of the bug `@capacitor/share` Capacitor plugin: https://github.com/ionic-team/capacitor-plugins/issues/2424. Created with Capacitor Create App.

- Clone
- Run in terminal:
```sh
npm i
npm run build
npx cap sync
cap open android
```
- Launch the app from Android studio - I've tested on real device
- Tap `TEST SHARE` button
- Choose the same app in sharing dialog - `ReproductionApp`
- Tap `TEST SHARE` again
- Check out alert with error message `Can't share while sharing is in progress` or the same error log in console.
