# Gitbook theme for ivoryhza

## Usage

Add the theme to your book's configuration `book.json` or `book.js`:

```js
{
    "plugins": [
        "theme-ivoryhza"
    ],
    "variables": {
        "themeIvoryhza":{
            // 顶部搜索框旁边的菜单
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
        "theme-ivoryhza":{
            // Meta
            "logo":"./logo.png", //logo地址
            "appleTouchIconPrecomposed152":"./logo.png", //logo地址
            "favicon": "./favicon.ico", //ico地址
            // 搜索框提示信息
            "search-placeholder":"搜索", 
            // PageFooter
            "copyright":"版权所有 © SOMECAT",
            "modify_label": "最后修订时间：",
            "modify_format": "YYYY-MM-DD",
            //TODO list:
            // // 颜色
            // "color_search_button": "",
            // "color_book_summary_menu_active": "",
            // "color_book_summary_menu_active_background": "",
            // "color_h1": "",
            // "color_h2": "",
            // "color_h3": "",
            // "color_h4": "",
            // "color_h5": "",
            // // 文案
            // "text_book_summary_title": "目录",
            // "text_book_anchor_title": "大纲",
            
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