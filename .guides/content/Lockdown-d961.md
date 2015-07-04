* Make sure you're in the loopback project directory:
```
$ pwd
/home/codio/workspace/loopback-zero-to-hero 
```

* If not, then get in there:
```
$ cd ~/workspace/loopback-zero-to-hero/
```

* Its easy to let the flexible versioning notations (`*`, `~` or `^`) in `package.json` fool us into working against different versions of dependencies! Since features and bugs vary across versions, let us make sure to work with exactly defined versions.

* Remove the following lines from `package.json` and save the file:
```
    "loopback": "^2.14.0",
    "loopback-boot": "^2.6.5",
    "loopback-datasource-juggler": "^2.19.0",
```

* Run these:
```
$ npm install --save --save-exact loopback#2.18.0
$ npm install --save --save-exact loopback-boot#2.8.1
$ npm install --save --save-exact loopback-datasource-juggler#2.31.0
```

* Examine your `package.json` file again and you should now see:
```
    "loopback": "2.18.0",
    "loopback-boot": "2.8.2",
    "loopback-datasource-juggler": "2.32.0",
```

* Good deal! onwards and upwards...