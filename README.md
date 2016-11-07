# Flickr search (Angular JS)

Based on [generator-gulp-angular ](https://github.com/Swiip/generator-gulp-angular/blob/master/README.md)

## Features

![Logo](docs/assets/gulp.png)
![Logo](docs/assets/angular.png)
![Logo](docs/assets/bootstrap.png)
![Logo](docs/assets/bower.png)
![Logo](docs/assets/webpack.png)
![Logo](docs/assets/karma.png)
![Logo](docs/assets/browsersync.png)
![Logo](docs/assets/jasmine.png)
![Logo](docs/assets/protractor.png)
![Logo](docs/assets/babel.png)
![Logo](docs/assets/sass.png)


[List features included](docs/usage.md#features-included-in-the-gulpfile)


## Usage

### Install

##### Install required tools `gulp` and `bower`:
```
npm install -g gulp bower
```

##### Clone this repo and goto its directory

##### Install node packages:
```
npm install
```

##### Install bower packages:
```
bower install
```

### Run

#### Use Gulp tasks

* `gulp` or `gulp build` to build an optimized version of your application in `/dist`
* `gulp serve` to launch a browser sync server on your source files
* `gulp serve:dist` to launch a server on your optimized application
* `gulp test` to launch your unit tests with Karma
* `gulp test:auto` to launch your unit tests with Karma in watch mode
* `gulp protractor` to launch your e2e tests with Protractor
* `gulp protractor:dist` to launch your e2e tests with Protractor on the dist files
