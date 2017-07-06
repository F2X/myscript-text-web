# myscript-text-web

The easy way to integrate text handwriting recognition in your web app.

![myscript-text-web preview](./preview.gif)

## What is it about?

myscript-text-web is a web component that can be used in every web application (whatever javascript framework you are using) to bring handwriting recognition. It integrates all you need:  
* Signal capture,
* Nice digital ink rendering,
* Plug with MyScript CDK to bring handwriting recognition.

## Prerequisites

1. Have a MyScript developer account. You can create one [here](https://dev.myscript.com/).
2. Get an application key and HMAC key for your application.
3. Import webcomponents polyfill on your webapp.

```html
    <script src="bower_components/webcomponentsjs/webcomponents-loader.js"></script>
```
 
## Installation

1. Download it.

       bower install myscript-text-web

2. Import it on your webapp.

```html
    <link rel="import" href="bower_components/myscript-text-web/myscript-text-web.html">
```

3. Configure it.

```html
    <myscript-text-web
        applicationkey="YOUR MYSCRIPT CDK APPLICATION KEY"
        hmackey="YOUR MYSCRIPT CDK HMAC KEY">
    </myscript-text-web>
```
   
4. Use it!

[Test it live](https://myscript.github.io/myscript-text-web/components/myscript-text-web/demo/)!

## Examples

- [demo/get_started.html](demo/get_started.html) Get started
- [demo/v4_configuration.html](demo/v4_configuration.html) Use interactive ink api (v4)
- [demo/handle_error.html](demo/handle_error.html) Handle error
- [demo/styling.html](demo/styling.html) Customize your component style
- [demo/programmatic_init.html](demo/programmatic_init.html) Programmatic initialization
- [demo/get_stats.html](demo/get_stats.html) Get statistics
- [demo/debug.html](demo/debug.html) Debug your component
- [demo/get_languages.html](demo/get_languages.html) Get available languages
- [demo/prediction_completion.html](demo/prediction_completion.html) Use prediction and completion
- [demo/superimposed.html](demo/superimposed.html) Use superimposed input mode
    
## Documentation 

The API Reference is available here: [https://myscript.github.io/myscript-text-web/](https://myscript.github.io/myscript-text-web/) 

## Contribute

We welcome your contributions:
If you would like to extend myscript-text-web for your needs, feel free to fork it!
Please sign our [Contributor License Agreement](CONTRIBUTING.md) before submitting your pull request.

## Share your feedback

Made a cool app with myscript-text-web? We would love to hear about you!
We’re planning to showcase apps using it so let us know by sending a quick mail to [myapp@myscript.com](mailto://myapp@myscript.com)

## License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
