# Cookieconsent (by orestbida)

This is a fork of orestbida cookieconsent script. I make this with little customisation to usage for Drupal sites. Any usage on your own risk.

There will be 5 languages in init file and language detection. Will work just if you have correctly set document language.

## Installation

Clone repository somewhere. In my case is it in files root.

```bash
cd sites/default/files
git clone https://github.com/masterwebsk/cookieconsent.git
```
If you choose another location, change path in init file and of course path to script ect in next steps.


# cookieconsent
orestbida cookieconsent clone - USE JUST IF YOU UNDERSTAND WHAT ARE YOU DOING :)
## Installation & Usage
1. Download the [latest release](https://github.com/orestbida/cookieconsent/releases/latest) or use via CDN or [NPM](https://www.npmjs.com/package/vanilla-cookieconsent)

    ```bash
    # CDN links
    https://cdn.jsdelivr.net/gh/orestbida/cookieconsent@v2.8.0/dist/cookieconsent.js
    https://cdn.jsdelivr.net/gh/orestbida/cookieconsent@v2.8.0/dist/cookieconsent.css
    ```

    Thanks to [Till Sanders](https://github.com/tillsanders) for bringing the plugin on npm.

    ```bash
    npm i vanilla-cookieconsent
    yarn add vanilla-cookieconsent
    ```

1. Import the plugin: add a `script` tag pointing to `cookieconsent.js`
    ```html
    <html>
        <head> <!-- head content --> </head>
        <body>
            <!-- body content -->
            <script defer src="<path-to-cookieconsent.js>"></script>
        </body>
    </html>
    ```
    <span>Note: replace `<path-to-cookieconsent.js>` with a valid path!</span>
    <br>

3. Configure and run
    -   <details><summary>As external script</summary>
        <p>

        - Create a `.js` file (e.g. `cookieconsent-init.js`) and import it in your html page

            ```html
            <body>
                <!-- body content ... -->
                <script defer src="<path-to-cookieconsent.js>"></script>
                <script defer src="<path-to-cookieconsent-init.js>"></script>
            <body>
            ```

        - Configure the plugin inside `cookieconsent-init.js`
