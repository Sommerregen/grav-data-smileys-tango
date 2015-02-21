# [Grav Smileys Data Pack -- Tango][project]

> Tango is a collection of smileys and emoticons from the [Tango Desktop Project](http://tango.freedesktop.org/).

## About

`Tango` is a lightweight collection of simple smileys extracted from the from the [Tango Desktop Project](http://tango.freedesktop.org/). It includes more than 16 smileys, each one having its own textual representation as can been seen [below](#contents).

![Screenshot Tango](assets/screenshot.png "Tango Preview")

## Installation

To install this data pack, just download the zip version of this repository and unzip it under `/your/site/grav/user/data/smileys`. Then, rename the folder to `tango`.

You should now have all the data pack files under

	/your/site/grav/user/data/smileys/tango

>> NOTE: This data pack is a modular component for Grav Smileys Plugin which requires [Grav](http://github.com/getgrav/grav), [Grav Smileys Plugin](https://github.com/sommerregen/grav-plugin-smileys) and a theme to be installed in order to operate.

## Usage

To activate and use `Grav Smileys Data Pack - Tango` the best process is to copy the [smileys.yaml](https://github.com/sommerregen/grav-plugin-smileys/smileys.yaml) file from the [Grav Smileys Plugin](https://github.com/sommerregen/grav-plugin-smileys) into your `users/config/plugins/` folder (create it if it doesn't exist), and  set the smileys package option to

```
pack: tango
```

You can then use any of the below smiley acronyms in your pages and `Grav Smileys Plugin` will automatically convert them to their icon graphic file equivalent. As an example

```
I love you <3
```

will then transform to

<code>I love you ![<3](kiss.png "heart <3")</code>

### Contents

`Grav Smileys Data Pack - Tango` comes [pre-configured](tango.yaml) with each smiley entry having the format

```
<your-smiley-file-without-extension>:
  enabled: true | false
  acronyms: "<your space separated acronyms e.g. :-) :)>"
  description: "<your description>"
```

In other words, smilies can be disabled separately by setting `enabled: false` or modified by setting your own description and/or smiley acronyms.

By default many smiley acronyms are supported. For a detailed list, please open the configuration file [tango.yaml](tango.yaml).

## Contributing

You can contribute at any time! Before opening any issue, please search for existing issues and review the [guidelines for contributing](CONTRIBUTING.md).

After that please note:

* If you find a bug or would like to make a feature request or suggest an improvement, [please open a new issue][issues]. If you have any interesting ideas for additions to the syntax please do suggest them as well!
* Feature requests are more likely to get attention if you include a clearly described use case.
* If you wish to submit a pull request, please make again sure that your request match the [guidelines for contributing](CONTRIBUTING.md) and that you keep track of adding unit tests for any new or changed functionality.

### Support and donations

If you like my project, feel free to support me via [![Flattr](https://api.flattr.com/button/flattr-badge-large.png)][flattr] or by sending me some bitcoins to **1HQdy5aBzNKNvqspiLvcmzigCq7doGfLM4**.

Thanks!

## License

Copyright (c) 2015 [Benjamin Regler][github]. See also the list of [contributors] who participated in this project.

1. **Grav Smileys Data Pack - Tango** is [licensed](LICENSE) for use under the terms of the [MIT license][mit-license].

2. **Tango** is [licensed](TANGO.LICENSE) for use under the terms of the [GPL v2 license][gpl-license].

[github]: https://github.com/sommerregen/ "GitHub account from Benjamin Regler"
[mit-license]: http://www.opensource.org/licenses/mit-license.php "MIT license"
[gpl-license]: http://opensource.org/licenses/GPL-2.0 "GPLv2 license"
[flattr]: https://flattr.com/submit/auto?user_id=Sommerregen&url=https://github.com/sommerregen/grav-data-smileys-tango "Flatter my GitHub project"

[project]: https://github.com/sommerregen/grav-data-smileys-tango
[issues]: https://github.com/sommerregen/grav-data-smileys-tango/issues "GitHub Issues for Grav Smileys Data Pack -- Tango"
[contributors]: https://github.com/sommerregen/grav-data-smileys-tango/graphs/contributors "List of contributors of the project"
