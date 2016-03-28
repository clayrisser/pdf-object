# &lt;pdf-object&gt;

An embeddable PDF viewer for [Polymer](https://www.polymer-project.org/1.0/)

View a live [Demo](http://jamrizzi.github.io/pdf-object/demo).


## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install pdf-object --save
```

Or [download as ZIP](https://github.com/jamrizzi/pdf-object/archive/v1.0.0.zip).


## Usage

Requires [Polymer 1.0](https://www.polymer-project.org/1.0/)

Read the [Docs](http://jamrizzi.github.io/pdf-object)

Example:
```html
<pdf-object file="http://www.polyu.edu.hk/iaee/files/pdf-sample.pdf"></pdf-object>
```

Example - with card enabled and elevation set to 5:
```html
<pdf-object file="[[pdfUrl]]" elevation="5" card></pdf-object>
```

Example - with data binding and custom height:
```html
<pdf-object file="[[pdfUrl]]" height="800px"></pdf-object>
```


## [Buy Me Coffee](http://jamrizzi.com/buy-me-coffee)

A ridiculous amount of coffee was consumed in the process of building this project. [Add some fuel](//jamrizzi.com/buy-me-coffee) if you'd like to keep me going!


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## Changelog

Take a peek at the [changelog](CHANGELOG.md).


## License

[GNU Public License v3](LICENSE)
