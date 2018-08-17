# phpdoc-sami-template

Like the visual style of [Sami](https://github.com/FriendsOfPHP/Sami), but want the capabilities of phpDocumentor (functions/namespaces)? This template is for you.

## Usage

Install this repository as a Composer dependency.

```bash
composer require humanmade/phpdoc-sami-template
```

Then use the path to the dependency as the `--template` value when running `phpdoc`:

```bash
phpdoc -d "./src" -t "./docs" --template="vendor/humanmade/phpdoc-sami-template"
```


## License

Created by Human Made, incorporating work from Sami and phpDocumentor. See [LICENSE](LICENSE) for full details.
