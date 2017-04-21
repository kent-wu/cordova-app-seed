# inception-app-demo

This is a cordova app project.

##Set up Cordova

if you have not install cordova, please run this commadn to install:

```
[sudo] npm install -g cordova
```

## Set up project

if you want to install this app to Android, run:

```
cordova platform add android
```

Maybe you also want to install this app to iOS, run:

```
cordova platform add ios
```

The changes of the code don't works until you redeploy to Mobile. 

You can run this command to add browser platform, so that you can test in browser.

```
cordova platform add browser
```

## Testing

After you run this command, it will watch files in the `www` folder and automatically reload HTML and CSS

```
cordova run browser -- --live-reload
```




