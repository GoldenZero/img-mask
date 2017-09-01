# &lt;img-mask&gt;

> A Polymer 2.0 element for masking the images with basic (and some extraordinary) geometric shap

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install img-mask --save
```

Or [download as ZIP](https://github.com/Goldenzero/img-mask/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="https://cdnjs.cloudflare.com/ajax/libs/webcomponentsjs/1.0.10/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="img-mask/img-mask.html">
    ```

3. Start using it!

    ```html
    <img-mask></img-mask>
    ```

## Options

Attribute       | Options                                                                                                       | Default                      | Description
---             | ---                                                                                                           | ---                          | ---
`shape`         | `circle`, `triangle`, `square`, `hexagon`, `octagon`, `star`, `rhombus`, `parallelogram`, `plus`, `squircle`, `ring`  | `circle`                     | The `shape` attribute sets a masking shape
`size`          | *int*                                                                                                         | `320`                        | The `size` attribute sets a size of an element
    `src`           | *string*                                                                                                  | `http://placehold.it/320`    | The `src` attribute defines a path to an image that will be masked
`href`          | *string*                                                                                                      | `-`                          | The `href` attribute sets the target URL
`title`         | *string*                                                                                                      | `-`                          | The `title` attribute sets a short description of an image. (It's not rendered visually by default.)
`desc`          | *string*                                                                                                      | `-`                          | The `desc` attribute sets a long description of an image. (It's not rendered visually by default.)

## Example

```html
<img-mask shape="circle" size="320" src="img/image.jpg" href="#" title="A short description of an image" desc="A long description of an image"></img-mask>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request ;)

## History

For detailed changelog, check [Releases](https://github.com/GoldenZero/img-mask/releases).

## License
[MIT License](http://opensource.org/licenses/MIT)
This component is inspired from https://github.com/hejty/image-mask