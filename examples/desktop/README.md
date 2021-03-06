This example application demonstrates the approach to localization
of Go desktop (command-line) applications, with the following properties:

 1. Display language is set manually
 2. Localization is stored in JSON files
 3. You can provide developer comments for each
    translatable entity
 4. Localization files are generated by
    [Serge](https://github.com/evernote/serge); generated .po files
    are used to provide translation (you can do a continuous
    localization of your project)
 5. Formatting (named placeholders, support for plurals/conditionals)
    is provided by [Plurr](https://github.com/iafan/Plurr) library
 6. Automatic generation of pseudotranslated resources for quick testing

See [.serge](.serge/) subfolder for an additional README on the localization workflow.

Running
-------

Use `./build.sh` script to build the binary, then run `./desktop-app`.