# Jekyll I18n support

Adds easy internationalisation support to your jekyll. Allows you to use a view helper to translate keys. Store the keys in yml files.

    // index.html
    <span>{% this_is_awesome %}</span>

    // _locales/en.yml
    this_is_awesome: Pure awesomeness.

## Instructions
1. Place the t.rb file in your _plugins directory.
2. Set an environment variable in your .bashrc or .zshrc:

        export JLANG="en"

3. Alternatively specify the locale in your _config.yml:

        locale: "en"
