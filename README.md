# Cookieconsent (by orestbida)

This is a fork of orestbida cookieconsent script. I made this with little customisation to usage for Drupal sites. Any usage on your own risk.

There will be 5 languages in `cookieconsent-init.js` file. Language detection will work just if you have correctly set document language.

## Installation

Clone repository somewhere. In my case is it files root.

```bash
cd sites/default/files
git clone https://github.com/masterwebsk/cookieconsent.git
```
If you choose another location, change path in init file and of course path to script ect in next steps.

Configure the plugin inside `cookieconsent-init.js`

If you want fresh or original files go to author url - [https://github.com/orestbida/cookieconsent](https://github.com/orestbida/cookieconsent)

## Usage

This can be done by several ways. In site template or via pasting code into block.
```html
<script defer src="/sites/default/files/cookieconsent/cookieconsent.js"></script>
<script defer src="/sites/default/files/cookieconsent/cookieconsent-init.js"></script>
<a href="javascript:void(0);" aria-haspopup="dialog" data-cc="c-settings">🍪 Change cookies settings</a>
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)