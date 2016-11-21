New Relic integration for your gitbook
==============

You can use install it via **NPM**:

```
$ npm install gitbook-plugin-new-relic
```

And use it for your book with in the book.json:

```
{
    "plugins": ["new-relic"]
}
```

You can set the New Relic licenseKey and applicationID using the plugins configuration in the book.json:

```
{
    "plugins": ["new-relic"],
    "pluginsConfig": {
        "newRelic": {
            "licenseKey": "XXXX"
            "applicationID": "XXXX"
        }
    }
}
```
