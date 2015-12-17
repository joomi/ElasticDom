# &lt;joomi&gt;

> An Awesome podcast player web-component

## Demo

[Check it live!](http://shay@joomi.co.il.github.io/joomi)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install joomi --save
```

Or [download as ZIP](https://github.com/shay@joomi.co.il/joomi/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/joomi/pod-cast.html">
    ```

3. Start using it!

    ```html
    <pod-cast></pod-cast>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`foo`         | *string*    | `bar`        | Lorem ipsum dolor.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

    ```sh
    $ npm install -g bower polyserve
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/my-repo/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.com/shay@joomi.co.il/joomi/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
