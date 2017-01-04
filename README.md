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

This will mean that the local climate-cli folder will be used in this project.  Also, you should copy the `env` file to `.env` and fill in the secrets.

# To Run

In one window (to run the climate service):
```
$> ./node_modules/.bin/climate s
```

In another window (to run the local server, which could include browserify/webpacking/etc):
```
$> npm start
```