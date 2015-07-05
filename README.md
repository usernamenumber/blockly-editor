# Blockly Editor
An interactive editor for [Blockly](https://github.com/google/blockly). Built mostly by cobbling together examples from the [Blockly installation docs](https://developers.google.com/blockly/installation/overview)

## Setup
1. On your web server, create a directory and `cd` into it
2. `git clone https://github.com/google/closure-library`
3. `git clone https://github.com/google/blockly`
4.  Make the `blockly` directory (parent of `blockly-editor`) accessible by your web server
4. `cd blockly`
5. `python build.py`
6. `git clone https://github.com/usernamenumber/blockly-editor/ editor`
7. visit `http://your-site/path/to/blockly/editor/`
