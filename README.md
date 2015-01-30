# pagination-table

See the [pagination-table](http://github.com/foohyfooh/pagination-table) for more information.

## Demo

[Check it live!](http://foohyfooh.github.io/pagination-table)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install pagination-table --save
```

Or [download as ZIP](https://github.com/foohyfooh/pagination-table/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/pagination-table/pagination-table.html">
    ```

3. Start using it!

    ```html
    <pagination-table items="{{items}}"></pagination-table>
    ```

## Options

Attribute       | Options     | Default            | Description
---             | ---         | ---                | ---
`items`         | *Array*     | `undefined`        | Items for component. JSON Objects.
`pageSize`      | *Number*    | `10`               | Number of items to display on page.
`layout`        | *String*    | `pagination-item`  | The tag to use to represent the items.


## Methods

Method             | Parameters   | Returns     | Description
---                | ---          | ---         | ---
`displayItems()`   | None.        | Nothing.    | Displays the items on the page.
`previousPage()`   | None.        | Nothing.    | Displays the previous page.
`nextPage()`       | None.        | Nothing.    | Displays the next page.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[MIT License](http://opensource.org/licenses/MIT)