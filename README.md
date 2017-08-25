## Thai Language Pack for [Flarum](http://flarum.org/)

Thai language package to localize Flarum and some supported extensions.

## Information
[![Latest Stable Version](https://poser.pugx.org/brarear/flarum-ext-thai/v/stable)](https://packagist.org/packages/brarear/flarum-ext-thai) [![Latest Unstable Version](https://poser.pugx.org/brarear/flarum-ext-thai/v/unstable)](https://packagist.org/packages/brarear/flarum-ext-thai) [![License](https://poser.pugx.org/brarear/flarum-ext-thai/license)](https://packagist.org/packages/brarear/flarum-ext-thai) [![Total Downloads](https://poser.pugx.org/brarear/flarum-ext-thai/downloads)](https://packagist.org/packages/brarear/flarum-ext-thai)

**Requires**: Flarum 0.1.0 Beta 7

### How to use
Flarum relies on [Composer](https://getcomposer.org/) to manage dependencies and extensions. Thai language packages are available in [Packagist](https://packagist.org/packages/brarear/flarum-ext-thai) and can be managed in the manner below. Make sure Composer is already installed on your computer, then follow these steps:

1. Run this command on your folder installing Flarum

       composer require brarear/flarum-ext-thai
           
   Don't forget to clear cache of your Flarum
       
       php flarum cache:clear

2. Go to the Flarum admin page, click **Extensions**, then check **Thai** for enable this extension.

The same command (in step 1) can be used to independently update the Thai language package (without updating anything else). Note that since the Thai language package will be added as a Flarum dependency, it will be automatically updated when you update Flarum and its dependencies through the Composer.


### Supported Extensions
When you install any or all of the extensions below, all the sentences in the extension will be translated into Thai.

> Supported extensions translate will support in next release.



### Notes
- So far it's almost 100% translated.
- Some sentences are translated by non-standard language. For example the word password remains I write the password (should be the password), and the word upload fixed I wrote upload (should upload).
- English subtitles still exist in yaml comment form, so you can help me to correct the translation.


## License
Released under the MIT License. Please see the [LICENSE](https://github.com/realodix/flarum-ext-indonesian/blob/master/LICENSE) file.
