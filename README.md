# Gitbook theme for ivoryhza

## Usage

Add the theme to your book's configuration `book.json` or `book.js`:

```js
{
    "plugins": [
        "theme-ivory"
    ],
    "variables": {
        "themeIvory":{
            "nav":[
                {
                    "url":"http://...",
                    "target":"_blank",
                    "name": "HOME"
                }
            ]
        },
    },
    "pluginsConfig": {
        "theme-ivory":{
            "search-placeholder":"搜索", //搜索框提示信息
            "logo":"./logo.png", //logo地址
            "appleTouchIconPrecomposed152":"./logo.png", //logo地址
            "favicon": "./favicon.ico", //ico地址
            // PageFooter
            "copyright":"&copy SOMECAT",
            "modify_label": "该文件修订时间：",
            "modify_format": "YYYY-MM-DD HH:mm:ss"
        }
    }
},
```

Install by command:

``` bash
gitbook install
```

## Recommand plugins

```js
plugins: [
    '-sharing',
    "-fontsettings",
    'back-to-top-button',
    "copy-code-button",
    "cuav-chapters",
    "heading-anchors",
    "theme-ivoryhza"
    //...
]
```


Enjoy!