# JS Beautify Wrapper for Sublime Text

useage:
1. install javascript beautify from package manager
2.cd .config/sublime-text-2/Packages/Javascript Beautify/libs
  git clone https://github.com/einars/js-beautify.git 


JS Beautify sublime default settings (the same as js-beautify settings),only add 
// jsbeautify options
  "format_on_save": true

```json
{
  "indent_size": 4,
  "indent_char": " ",
  "indent_level": 0,
  "indent_with_tabs": false,
  "preserve_newlines": true,
  "max_preserve_newlines": 10,
  "jslint_happy": false,
  "brace_style": "collapse",
  "keep_array_indentation": false,
  "keep_function_indentation": false,
  "space_before_conditional": true,
  "break_chained_methods": false,
  "eval_code": false,
  "unescape_strings": false,
  "wrap_line_length": 0,

  // jsbeautify options
  "format_on_save": true
}
```

# License

You are free to use this in any way you want, in case you find this
useful or working for you but you must keep the copyright notice and license. (MIT)

# Credits
* Written by Edwin Liu, <enginespot@gmail.com>
* Get Idea from JsFormat Library by Davis Clark