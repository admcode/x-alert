# &lt;x-alert&gt;

Web Component for display alert content your message

> Maintained by [admcode](https://github.com/admcode).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/x-alert.html">
    ```

3. Start using it!

    ```html
    <x-alert text="Start using it!" type="info"></x-alert>
    ```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [NodeJS](http://nodejs.org/download/).
2. Install [GruntJS](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```

## Options

Attribute  | Options                                | Default
---        | ---                                    | ---
`type`     | `notify`, `warning`, `success`, `info` | `info`
`text`     | *string*                               | `Your text here`

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/webcomponents/element-boilerplate/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)