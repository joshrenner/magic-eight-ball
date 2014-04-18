&lt;magic-eight-ball&gt;
========================

A [Polymer](http://polymer-project.org) element for a magic eight ball

> Maintained by [Josh Renner](https://github.com/press22day).

## Demo

> [Check it live](http://press22day.github.io/magic-eight-ball).

```html
<magic-eight-ball outlook="-1|0|1">
	<option outlook="-1|0|1"></option>
</magic-eight-ball>
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="src/magic-eight-ball.html">
```

3. Start using it!

```html
<magic-eight-ball><magic-eight-ball>
```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [bower](http://bower.io/)
2. Install local dependencies:

```sh
$ bower install
```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`outlook`  | *string*                  | `0`                 | 1 for optimism, 0 for neutral, -1 for pessimism


## License

[MIT License](http://opensource.org/licenses/MIT)
