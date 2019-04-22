# Sublime Setup
Personal sublime settings and plugins - for easy referencing

## Version
3.1.1

## Settings

```
{
	"color_scheme": "Packages/Materialize/schemes/Material Monokai Soda.tmTheme",
	"font_size": 10,
	"ignored_packages":
	[
		"Vintage"
	],
	"match_brackets": false,
	"match_brackets_angle": false,
	"match_brackets_braces": false,
	"match_brackets_content": false,
	"match_brackets_square": false,
	"match_tags": false,
	"tab_size": 2,
	"theme": "Material Brogrammer.sublime-theme",
	"translate_tabs_to_spaces": true,
	"word_wrap": true
}

```

## Plugins

  - Alignment
  ```
  {
      // The mid-line characters to align in a multi-line selection, changing
      // this to an empty array will disable mid-line alignment
      "alignment_chars": [
          "=", ":"
      ]
  }
  ```
  - AutoFileName
  - BracketHighlighter
  - Emmet
  ```
  //Default(Windows).sublime-keymap
  {
    "keys": [
      "tab"
    ],
    "args": {
      "action": "expand_abbreviation"
    },
    "command": "run_emmet_action",
    "context": [
      {
        "key": "emmet_action_enabled.expand_abbreviation"
      }
    ]
  }
  ```
  - HTMLBeautify
  - Markdown Editing
  - JSBeautify  
  - PHPIntel
  - PHPSnippets
  - SASS
  - SASSBeautify
  - SublimeLinter
    - anotations
    - jshint
    - phplint
    - pylint
  - Pretty JSON