# selenium01
Simple selenium protractor angular project

# Install steps
```
npm init
```

Instrall protractor, jasmine and the tiny http-server
```
npm install --save protractor jasmine http-server
```

Init jasmine
```
jasmine init
```

Installa webdriver
```
./node_modules/protractor/bin/webdriver-manager	update
```

Copy conf file
```
cp ./node_modules/protractor/example/conf.js test/
```

# Start selenium
```
./node_modules/protractor/bin/webdriver-manager	start
```

# Check config:
To see more options
Check this [https://github.com/angular/protractor/blob/master/docs/referenceConf.js]
