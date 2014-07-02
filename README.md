# &lt;x-instagram&gt;

A [Polymer](http://polymer-project.org) element for querying results from the [Strava API](http://strava.github.io/api/)

> Maintained by [Brent Vatne](https://github.com/brentvatne).

## Install

Using [Bower](http://bower.io), run:

```bash
$ bower install --save strava-card
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="src/strava-card.html">
```

3. Start using it!

```html
<strava-card athlete-id="yourathleteidinteger"></strava-card>
```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [Node.js](http://nodejs.org/download/)
2. Install [Grunt](http://gruntjs.com/):

```sh
$ npm install -g grunt-cli
```

3. Install local dependencies:

```sh
$ npm install
```

4. Run a local server and open `http://localhost:8000`.

```sh
$ grunt connect
```

## License

[MIT License](http://opensource.org/licenses/MIT)
