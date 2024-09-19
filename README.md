# React Draft Wysiwyg Simple

- this is modyfied version of original library react draft wysywig.(Author Jota Puri),author of modification:yaumamyfront-ender==>
- added function when you can change icon in option(buttons in toolbar)and they work like button on/off
- how to use this feature?
- 1.read original documentation how to use tooolbar options/toolbar property/ in original documentation

- 2.copy newArrayOfDependencies(toolbarOptions) from txt file and put htem to your new toolbaroptions file in your projects(you find info in origin documentation)

- 3.copy css from css-to-add and put to your new css file and link them to library(you find info in origin documentation)

- 3.find iconOnClick(toolbarOptions) in array and then add your icon
- use it :-
- \*\*\*\*in development
- easy function to get all generated html from editor and send this to server(like in next.js)==>in development(in folder temp you can get this if you wanna implement this now but unfortanately i dont do this at the time)
- all function in tolbar easy switch
- ===================================================================================================================================================================================================
- #this is original description of original project below down==>

# React Draft Wysiwyg

A Wysiwyg editor built using ReactJS and DraftJS libraries.
[Demo Page](https://jpuri.github.io/react-draft-wysiwyg).

[![Build Status](https://travis-ci.org/jpuri/react-draft-wysiwyg.svg?branch=master)](https://travis-ci.org/jpuri/react-draft-wysiwyg)

![](http://i.imgur.com/tU7kJ6i.gif)

## Features

- Configurable toolbar with option to add/remove controls.
- Option to change the order of the controls in the toolbar.
- Option to add custom controls to the toolbar.
- Option to change styles and icons in the toolbar.
- Option to show toolbar only when editor is focused.
- Support for inline styles: Bold, Italic, Underline, StrikeThrough, Code, Subscript, Superscript.
- Support for block types: Paragraph, H1 - H6, Blockquote, Code.
- Support for setting font-size and font-family.
- Support for ordered / unordered lists and indenting.
- Support for text-alignment.
- Support for coloring text or background.
- Support for adding / editing links
- Choice of more than 150 emojis.
- Support for mentions.
- Support for hashtags.
- Support for adding / uploading images.
- Support for aligning images, setting height, width.
- Support for Embedded links, flexibility to set height and width.
- Option provided to remove added styling.
- Option of undo and redo.
- Configurable behavior for RTL and Spellcheck.
- Support for placeholder.
- Support for WAI-ARIA Support attributes
- Using editor as controlled or un-controlled React component.
- Support to convert Editor Content to HTML, JSON, Markdown.
- Support to convert the HTML generated by the editor back to editor content.
- Support for internationalization.

## Installing

The package can be installed from npm `react-draft-wysiwyg`

```
$ npm install --save react-draft-wysiwyg draft-js
```

## Getting started

Editor can be used as simple React Component:

```js
import { Editor } from "react-draft-wysiwyg";
import "react-draft-wysiwyg/dist/react-draft-wysiwyg.css";
<Editor
  editorState={editorState}
  toolbarClassName="toolbarClassName"
  wrapperClassName="wrapperClassName"
  editorClassName="editorClassName"
  onEditorStateChange={this.onEditorStateChange}
/>;
```

## Docs

For more documentation check [here](https://jpuri.github.io/react-draft-wysiwyg/#/docs?_k=jjqinp).

## Questions Discussions

For discussions join public channel #rd_wysiwyg in [DraftJS Slack Organization](https://draftjs.herokuapp.com/).

## Fund

You can fund project at [Patreon](https://www.patreon.com/jyotipuri).

## Thanks

Original motivation and sponsorship for this work came from [iPaoo](http://www.ipaoo.com/). I am thankful to them for allowing the Editor to be open-sourced.

## License

MIT.
