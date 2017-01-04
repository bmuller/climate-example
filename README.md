# Climate Example App

For local development, first go into your climate-cli directory and run:
```
$> yarn link
```

Then, in the climate-example folder:
```
$> yarn
$> yarn link climate-cli
$> yarn add file:../climate-cli
```

This will mean that the local climate-cli folder will be used in this project.

# To Run

In one window (to run the climate service):
```
$> yarn run climate s
```

In another window (to run the local server, which could include browserify/webpacking/etc):
```
$> npm start
```