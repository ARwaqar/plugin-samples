# Plugin Samples

This repository contains several sample XD plugins. You can use these to learn more about how to build plugins for Adobe XD. Make sure to read the README or instructions commented in the `main.js` file. Note that samples that start with `how-to-` has their companion guides in the [Plugin-Docs repository](https://github.com/AdobeXD/Plugin-Docs/)

## Samples list

| Extension | Main APIs Used | Description | Minimum Version |
| --- | ------ | --- | --- |
| e2e-adobe-stock | Network I/O (Fetch) | Lets users use End-to-end Adobe Stock Photo Search | 10.0.10.24 |
| e2e-colorize-text | Scenegraph, ScenenodeList | Provides several text color utilities | 12.0.10.64 |
| e2e-stock-chart | UI, File I/O, Scenegraph, Network I/O (Fetch)  | Draws a line chart of the picked stock quote | 10.0.10.24 |
| getting-started | Scenegraph  | Creates a text ("Hello!") object and inserts it into the artboard | 8.0 |
| how-to-ask-user-for-confirmation | UI | Demonstrates how to build a user confirmation dialog | 8.0 |
| how-to-create-path-objects | Scenegraph | Demonstrates how to create shapes using path objects | 8.0 |
| how-to-display-an-image | UI | Demonstrates how to add an image in the modal UI | 10.0.10.24 |
| how-to-draw-lines | Scenegraph | Demonstrates how to create line objects | 8.0 |
| how-to-generate-an-export-rendition | File I/O, Application(renditions) | Demonstrates how to generate an export rendition of an object | 10.0.10.24 |
| how-to-import | File I/O, Scenegraph | Demonstrates how to import a `.txt` file | 10.0.10.24 |
| how-to-integrate-with-OAuth | Network I/O (XHR, openExternal), Node.js server | Demonstrates how to integrate with a third-party OAuth | 10.0.10.24 |
| how-to-make-network-requests | Network I/O (XHR , Fetch), Scenegraph | Demonstrates how to make network requests | 10.0.10.24 |
| how-to-style-text | Scenegraph | Demonstrates how to create text nodes with styled text | 10.0.10.24 |
| how-to-use-single-line-text-ui | UI, Scenegraph | Demonstrates how to take user input from the modal dailog and insert the text | 10.0.10.24 |
| how-to-use-websockets | UI, Network I/O (Websockets), Node.js server | Demonstrates how to use websockets to communicate with an exernal server | 10.0.10.24 |
| how-to-work-with-scenenodelist | Scenegraph | Demonstrates how to create various objects and use scenenode list to filter and color | 8.0 |
| sg-chart-generator | Scenegraph, Commands | Demonstrates how to generate pie charts and bar charts | 8.0 |
| sg-dummy-data | Scenegraph, Commands | Demonstrates how to generate random data | 8.0 |
| sg-dynamic-button | Scenegraph, Commands | Updates a frame shape to wrap a text element exactly with a specified amount of padding | 8.0 |
| sg-fit-to-object | Scenegraph, Commands | Fits an object (image) to another object (rectangle) with three options- as-is, turn clockwise, turn counter-clockwise | 8.0 |
| sg-lots-of-lines | Scenegraph | Draws multiple lines | 8.0 |
| sg-margin-guides | Scenegraph, Commands | Create/remove margin guides around the existing objects in artboard(s) | 8.0 |
| sg-meme-me | Scenegraph, Commands | Takes text inputs and an image and convert them into a meme | 8.0 |
| sg-randomizer | Scenegraph, Commands | Duplicates the selection randomly around the artboard | 8.0 |
| sg-repeater | Scenegraph, Commands | Duplicates the selection horizontally or circularly | 8.0 |
| sg-simple-to-html | Scenegraph, Commands | Converts the selected shapes (paths, text, rectangles) into HTML | 8.0 |
| sg-turtle | Scenegraph, Commands | Draws a series of lines by following "turtle graphics" commands | 8.0 |
| sg-update-weather | Scenegraph, Network I/O (XHR) | Finds all text elements that follow a specific pattern and insert the temperatures | 8.0 |
| ui-button-padding | UI | Uses `h` function to create a simple UI with these UI elements: form, labrel, footer | 10.0.10.24 |
| ui-button-padding-hyperscript | UI | Uses hyperscript to create these UI elements: form, labrel, footer | 10.0.10.24 |
| ui-buttons-galore | UI | Uses `document.querySelector` to create these UI elements: different types of buttons | 10.0.10.24 |
| ui-context-menu | UI | Uses `h` function to create a context menu with these UI elements: form, footer, button | 10.0.10.24 |
| ui-create-chart | UI | Uses `h` function to create a menu optimized for generating charts with these UI elements: form, footer, button | 10.0.10.24 |
| ui-datagrid-react | UI | Uses React to create data grids | 10.0.10.24 |
| ui-dialog-variations | UI | Demonstrates several different dialog variations | 10.0.10.24 |
| ui-hello | UI | Simply shows a dialog with "Hello World" | 10.0.10.24 |
| ui-hello-h | UI | Used `h` function to simply show a dialog with "Hello World" | 10.0.10.24 |
| ui-hello-react-jsx | UI | Used React jsx to simply show a dialog with "Hello World" | 10.0.10.24 |
| ui-hello-react-raw | UI | Used React to simply show a dialog with "Hello World" | 10.0.10.24 |
| ui-hello-vue | UI | Used Vue to simply show a dialog with "Hello World" | 10.0.10.24 |
| ui-html | UI | Creates a dialog showing simple UI elements: title, text, input field, and buttons | 10.0.10.24 |
| ui-jquery | UI | Used jquery to create a dialog showing simple UI elements: title, text, input field, and buttons | 10.0.10.24 |
| ui-playground | UI | Shows all the controls in a playground | 10.0.10.24 |
| ui-rename-artoboards | UI | Shows a sample UI for a plugin that renames artboards | 10.0.10.24 |
| ui-simple-form | UI | Shows a simple form with these UI elements: input, textarea, select, button | 10.0.10.24 |
| ui-trello | UI | Uses `h` function to create a UI that's suitable for a workflow management plugin like Trello  | 10.0.10.24 |
| ui-vectorize | UI | Uses `h` function to create a simple UI with these UI elements: title, text, button  | 10.0.10.24 |


## Recommended development setup

1. Go to this directory (Mac or Windows):

   Mac: `cd ~/Library/Application\ Support/Adobe/Adobe\ XD\ CC\ \(Prerelease\)/`

   Windows: `C:\Users\your-username-here\AppData\Local\Packages\Adobe.CC.XD.Prerelease_adky2gkssdxte\LocalState\`

2. Rename the "plugins" directory if any

    Mac: `mv plugins oldplugins`
    Windows: (use Windows Explorer)

3. Checkout this repository as the "plugins" directory.

    `git clone git@github.com:AdobeXD/Plugin-Samples.git plugins`

4. Launch XD and start a new Document.

5. Use COMMAND+SHIFT+R to reload plugins.

6. Launch plugins from the `Plugins` menu.

Make sure to check out [XD Plugin Guides](https://adobe-xd.gitbook.io/plugin-guides/) and [XD Plugin References](https://adobe-xd.gitbook.io/plugin-api-reference).