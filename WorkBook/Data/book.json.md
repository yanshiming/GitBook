{
    "title": "My Work Book",
    "description": "运维知识库",
    "author": "yansm",
    "output.name": "site",
    "language": "zh-hans",
    "gitbook": "3.2.3",
    "root": ".",
    "structure": {
        "readme": "README.md"
    },
    "links": {
        "sidebar": {
            "Home": "http://localhost:4000"
        }
    },
    "plugins": [
        "-lunr",
        "-search",
        "-highlight",
        "-livereload",
        "search-plus@^0.0.11",
        "simple-page-toc@^0.1.1",
        "edit-link@^2.0.2",
        "prism@^2.1.0",
        "prism-themes@^0.0.2",
        "advanced-emoji@^0.2.1",
        "anchors@^0.7.1",
        "include-codeblock@^3.0.2",
        "ace@^0.3.2",
        "emphasize@^1.1.0",
        "katex@^1.1.3",
        "splitter@^0.0.8",
        "mermaid-gb3@2.1.0",
        "tbfed-pagefooter@^0.0.1",
        "expandable-chapters-small@^0.1.7",
        "sectionx@^3.1.0",
        "local-video@^1.0.1",
        "sitemap-general@^0.1.1",
        "anchor-navigation-ex@0.1.8",
        "favicon@^0.0.2",
        "todo@^0.1.3",
        "3-ba@^0.9.0",
        "terminal@^0.3.2",
        "alerts@^0.2.0",
        "include-csv@^0.1.0",
        "puml@^1.0.1",
        "musicxml@^1.0.2",
        "klipse@^1.2.0",
        "versions-select@^0.1.1",
        "-sharing",
        "sharing-plus@^0.0.2",
        "graph@^0.1.0",
        "chart@^0.2.0",
        "toggle-chapters",
        "multipart"
    ],

    "pluginsConfig": {
        "theme-default": {
            "showLevel": true,
            "style": "ebook"
        },
        "prism": {
            "css": [
                "prism-themes/themes/prism-base16-ateliersulphurpool.light.css"
            ]
        },
        "include-codeblock": {
            "template": "ace",
            "unindent": true,
            "edit": true
        },
        "sharing": {
           "douban": false,
           "facebook": false,
           "google": true,
           "hatenaBookmark": false,
           "instapaper": false,
           "line": false,
           "linkedin": true,
           "messenger": false,
           "pocket": false,
           "qq": true,
           "qzone": false,
           "stumbleupon": false,
           "twitter": false,
           "viber": false,
           "vk": false,
           "weibo": true,
           "whatsapp": false,
           "wechat": true,
           "all": [
               "facebook", "google", "twitter",
               "weibo", "instapaper", "linkedin",
               "pocket", "stumbleupon", "qq", "qzone"
           ]
       },
        "tbfed-pagefooter": {
            "copyright": "Copyright © yansm.com 2018",
            "modify_label": "该文件修订时间：",
            "modify_format": "YYYY-MM-DD HH:mm:ss"
        },
        "3-ba": {
            "token": "ff100361cdce95dd4c8fb96b4009f7bc"
        },
        "simple-page-toc": {
            "maxDepth": 3,
            "skipFirstH1": true
        },
        "edit-link": {
            "base": "https://github.com/zhangjikai/gitbook-use/edit/master",
            "label": "Edit This Page"
        },
        "sitemap-general": {
            "prefix": "http://gitbook.yansm.com"
        },
        "anchor-navigation-ex": {
            "isRewritePageTitle": false,
            "tocLevel1Icon": "fa fa-hand-o-right",
            "tocLevel2Icon": "fa fa-hand-o-right",
            "tocLevel3Icon": "fa fa-hand-o-right"
        },
        "sectionx": {
            "tag": "b"
        },
        "favicon": {
            "shortcut": "favicon.ico",
            "bookmark": "favicon.ico"
        },
        "terminal": {
            "copyButtons": true,
            "fade": false,
            "style": "flat"
        },
        "versions": {
            "options": [
                {
                    "value": "http://gitbook.yansm.com",
                    "text": "v3.2.3"
                },
                {
                    "value": "http://gitbook.yansm.com/v2/",
                    "text": "v2.6.4"
                }
            ]
        }

    }
}
