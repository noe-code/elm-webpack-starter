# elm-webpack-starter

A simple Webpack setup for writing [Elm](http://elm-lang.org/) apps:

* Dev server with live reloading
* Support for CSS/SCSS, with Autoprefixer
* Bundling and minification for deployment
* Basic app scaffold, integrating Elm's official [StartApp](https://github.com/evancz/start-app) package
* A snippet of example code to get you started!

### Install

Clone repository:

```console
$ git clone git@github.com:noe-code/elm-webpack-starter
```

Delete the existing `git` repository:

```console
$ rm -rf .git
```

Initialize your own repository:

```console
$ git init
```

Install `node` dependencies:

```console
$ npm install
```

Install `elm` dependencies:

```console
$ elm-package install
```

### Serve locally

```console
$ npm run start
```

* Access app at `http://localhost:8080/`
* Get coding! The entry point file is `src/Main.elm` 
* Browser will refresh automatically on any file changes..


### Build for production

```console
$ npm run build
```

* Files are saved into the `/dist` folder