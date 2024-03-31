# mdfaisal-tealcrow README

## Description

This theme contains the beautiful colors of teal and orange as primary colors and plays with other complementary colors to bring out the best dark theme with many color distinctions. This allows coders to identify all syntax and keywords clearly with precision. This can be used with any language, but languages like JavaScript (js), JSX, TypeScript (ts), TSX, Vue.js (vue), PHP, HTML, CSS, and SCSS are prioritized for design.

<div>
  <div align="center">
    <p>Javascript syntax highlight</p>
    <img src="https://github.com/acej0k3r/mdfaisal-tealcrow/blob/main/images/script.png" alt="html-body-code"/> 
  </div>
  <div align="center">
    <p>HTML body syntax highlight</p>
    <img src="https://github.com/acej0k3r/mdfaisal-tealcrow/blob/main/images/htmlBody.png" alt="html-body-code"/> 
  </div>
</div>

<div>
  </br>
</div>


## Add semanticTokenColorCustomizations, tokenColorCustomizations, and the extension TODO highlight for intended experience

 <div align="center">
    </br>
    <b><p>For best user experience for VUE/NUXT, install the TODO highlight extension by Wayou Liu, and copy paste the JSON code below into your settings.json<p></b>
    </br>
    </br>
  </div>
  
  
```json
"editor.semanticTokenColorCustomizations": {
    "[Teal-Crow by Faisal]": {
        "enabled": true,
        "rules": {
            //modify as needed
            "*.generic": "#e28c67",
            "variable.other.object": "#e28c67",
            "variable.other.object.ts": "#e28c67",
            "meta.directive.show.vue-html": "#e28c67",
            "meta.parameter.type.variable": "#e28c67"
        }
    }
}, 

//you can target other tokenColorCustomization using the following code
"editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "keyword.control.conditional",
        "settings": {
          "foreground": "#1a967b",
          "fontStyle": "bold underline"
        }
      },
      {
        "scope": "keyword.control.loop",
        "settings": {
          "foreground": "#985ea1",
          "fontStyle": "bold underline"
        }
      },
      {
        "scope": "meta.directive.show.vue-html",
        "settings": {
          "fontStyle": "underline"
        }
      },
      {
        "scope": ["entity.name.tag", "punctuation.definition.tag"],
        "settings": {
          "foreground": "#e6ddddbe"
        }
      },
      {
        "scope": "entity.name.section.vue",
        "settings": {
          "foreground": "#ff0000c7",
          "fontStyle": "bold"
        }
      }
    ]
  },
  
  //YOU CAN ALSO USE THE TODO Highlight by Wayou Liu to get additional syntax support
  "todohighlight.isEnable": true,
  "todohighlight.keywords": [
    {
      "text": "v-show",
      "color": "#e71848",
      "backgroundColor": "#000",
      "overviewRulerColor": "grey"
    },
    {
      "text": "v-if",
      "color": "#1a967b",
      "backgroundColor": "#000",
      "overviewRulerColor": "grey"
    },
    {
      "text": "v-else-if",
      "color": "#1a967b",
      "backgroundColor": "#000",
      "overviewRulerColor": "grey"
    },
    {
      "text": "v-else",
      "color": "#1a967b",
      "backgroundColor": "#000",
      "overviewRulerColor": "grey"
    },
    {
      "text": "v-for",
      "color": "#985ea1",
      "backgroundColor": "#000",
      "overviewRulerColor": "grey"
    },
    {
      "text": "div",
      "color": "#7B7FA1",
      "backgroundColor": "transparent",
      "fontStyle": "bold",
      "overviewRulerColor": "grey"
    }
  ]

```

## Contact

If you have any questions or requests, please feel free to contact me via:


-[LinkedLn](https://www.linkedin.com/in/md-a-faisal-2b3070139/)
-[GitHub](https://github.com/acej0k3r) 

