https://webdriver.io/docs/gettingstarted.html

$ mkdir webdriverio-test && cd webdriverio-test
$ npm init -y
$ npm i --save-dev @wdio/cli
$ npx wdio config -y
$ mkdir .\test\specs
$ touch ./test/specs/basic.js
$ npx wdio wdio.conf.js
