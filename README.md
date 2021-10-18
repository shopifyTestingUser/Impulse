# Impulse - template shopify
### Installation Shopify CLI:

* Download the latest version of the shopify-cli-x.y.z.deb file: https://github.com/Shopify/shopify-cli/releases
* ```sudo apt install /path/to/download/shopify-cli-x.y.z.deb``` - установи Shopify CLI
* To verify that Shopify CLI is installed properly, run the following command: ```shopify version```

### Preview, test, and share your theme
* To serve your theme, run the following command: ``` shopify theme serve ```

#### Shopify CLI uploads the theme as a development theme on the store that you're connected to, and returns the following:

* A link to your development theme at http://127.0.0.1:9292. This URL hot reloads local changes to CSS and sections, allowing you to preview changes in real time using the store's data. This preview is available only in Google Chrome.
* A link to the online store editor for the theme.
* A preview link that you can share with others.
