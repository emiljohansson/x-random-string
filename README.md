# &lt;random-string&gt;

> A web component that generates a random string [0-9][A-Z][a-z].

## Demo

[Check it live!](http://emiljohansson.github.io/random-string)

## Install

Install the component using [Bower](http://bower.io/):

Or [download as ZIP](https://github.com//emiljohansson/random-string/archive/update-to-latest-standard.zip).

```sh
$ bower install random-string --save
```

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/random-string/random-string.html">
    ```

3. Start using it!

    ```html
    <random-string></random-string>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`length`      | *integer*   | `10`         | The number of characters.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`generate()`  | None.        | Nothing.    | Generates a new string.
`limit()`     | None.        | int.        | The maximum number of characters.

## Events

Event           | Description
---             | ---
`lengthChanged` | Triggers a new string to generate.

## History

For detailed changelog, check [Releases](https://github.com/emiljohansson/random-string/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
