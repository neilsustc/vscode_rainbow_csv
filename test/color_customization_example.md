### Colors customization 

Add the json fragment below to VS Code settings to modify Rainbow CSV colors and increase contrast.  
This will not affect syntax colors for other file types.  
You can modify "foreground" and "fontStyle" attributes as you like.  

```
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": "rainbow1",
            "settings": {
               "foreground": "#E6194B"
            }
        },
        {
            "scope": "keyword.rainbow2",
            "settings": {
               "foreground": "#3CB44B",
               "fontStyle": "bold"
            }
        },
        {
            "scope": "entity.name.function.rainbow3",
            "settings": {
               "foreground": "#FFE119",
               "fontStyle": "italic"
            }
        },
        {
            "scope": "comment.rainbow4",
            "settings": {
               "foreground": "#0082C8",
               "fontStyle": "underline"
            }
        },
        {
            "scope": "string.rainbow5",
            "settings": {
               "foreground": "#FABEBE"
            }
        },
        {
            "scope": "variable.parameter.rainbow6",
            "settings": {
               "foreground": "#46F0F0",
               "fontStyle": "bold"
            }
        },
        {
            "scope": "constant.numeric.rainbow7",
            "settings": {
               "foreground": "#F032E6",
               "fontStyle": "italic"
            }
        },
        {
            "scope": "entity.name.type.rainbow8",
            "settings": {
               "foreground": "#008080",
               "fontStyle": "underline"
            }
        },
        {
            "scope": "markup.bold.rainbow9",
            "settings": {
               "foreground": "#F58231"
            }
        },
        {
            "scope": "invalid.rainbow10",
            "settings": {
               "foreground": "#FFFFFF"
            }
        }
    ]
}
```

#### Rainbow CSV after color customization

![customized colors](https://i.imgur.com/45EJJv4.png)
