# React-Redux-Docker-Ngnix-Seed

 - [React](https://github.com/facebook/react)
 - [Redux](https://github.com/reactjs/react-redux)
 - Router
 - Auth-Components
 - [SocketIO](https://github.com/socketio/socket.io)
 - [Webpack](https://webpack.github.io/)

Style

 - [Sass](http://sass-lang.com/)
 - [Material-UI](http://www.material-ui.com/#/)
 - [CSSModules](https://github.com/css-modules/css-modules)

Dev

 - [Docker](https://www.docker.com/)
 - [Ngnix](https://www.nginx.com/resources/wiki/)
 
Test
 
 - [Selenium](http://www.seleniumhq.org/)
 - [Mocha](https://mochajs.org/)
 - [Karma](https://karma-runner.github.io/1.0/index.html)


--------------

## Dependencies for selenium

- Docker
- Selenium server listening on port **4444**



## npm scripts

### Dev
```bash
$ npm run dev
```

This runs a development mode server with live reload etc.

Open `http://localhost:3000` in your browser.


### Tests

#### All tests
```bash
$ npm run test
```

#### Unit tests
```bash
$ npm run test:unit
```

#### End to end tests (Selenium)
```bash
$ npm run test:e2e
```

#### Coverage
```bash
$ npm run codecov
```

###Deploy

#### Deploy Dev
```bash
$ npm run deploy:dev
```

#### Deploy Prod
```bash
$ npm run deploy:prod
```


## License

Copyright (c) 2016 Shy Alter

[MIT License][MIT]

[MIT]: ./LICENSE "Mit License"
