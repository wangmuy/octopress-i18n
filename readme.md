# Jekyll I18n support

Adds easy internationalisation support to your jekyll. Allows you to use a view helper to translate keys. Store the keys in yml files.

    // index.html
    <span>{% i18n this_is_awesome %}</span>

    // source/_locales/en.yml
    this_is_awesome: 酷毙了

## Instructions
1. Place the i18n.rb file in your source/_plugins directory.
2. Set an environment variable in your .bashrc or .zshrc:

        export OCTOPRESS_LANG="zh_CN"

3. Alternatively specify the locale in your _config.yml:

        locale: "zh_CN"
