<!-- Please do not edit this file. Edit the `blah` field in the `package.json` instead. If in doubt, open an issue. -->


# regex-escape

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Ask me anything](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/regex-escape.svg)](https://www.npmjs.com/package/regex-escape) [![Downloads](https://img.shields.io/npm/dt/regex-escape.svg)](https://www.npmjs.com/package/regex-escape)

> Escapes input characters to be used in regular expressions.

## :cloud: Installation

```sh
# Using npm
npm install --save regex-escape

# Using yarn
yarn add regex-escape
```


## :clipboard: Example



```js
// Dependencies
var RegexEscape = require("regex-escape");

console.log(RegexEscape("{#/}"));
// => \{#\/\}
```



## :question: Get Help

There are few ways to get help:

 1. Please [post questions on Stack Overflow](https://stackoverflow.com/questions/ask). You can open issues with questions, as long you add a link to your Stack Overflow question.
 2. For bug reports and feature requests, open issues. :bug:

 3. For direct and quick help, you can [use Codementor](https://www.codementor.io/johnnyb). :rocket:



## :memo: Documentation


### `RegexEscape(input)`
Escapes a string for using it in a regular expression.

#### Params

- **String** `input`: The string that must be escaped.

#### Return
- **String** The escaped string.

### `proto()`
Adds the `RegexEscape` function to `RegExp` class.

#### Return
- **Function** The `RegexEscape` function.



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![Buy me a book][badge_amazon]][amazon]—I love books! I will remember you after years if you buy me one. :grin: :book:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:


## :cake: Thanks
Big thanks to [CoolAj86](http://stackoverflow.com/users/151312/coolaj86) for posting [this answer](http://stackoverflow.com/a/6969486/1420197). This library uses the black magic regex from that answer. :sparkles:

## :dizzy: Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:


 - [`barbe`](https://github.com/IonicaBizau/barbe)—Like mustache, but simple, tiny and fast.
 - [`bloggify-router`](https://github.com/Bloggify/default-router#readme) (by Bloggify)—The default Bloggify router.
 - [`camelo`](https://github.com/IonicaBizau/camelo#readme)—Convert a string into camel case style by providing the separators.
 - [`chance-token-replacer`](https://github.com/drewbrokke/chance-token-replacer#readme) (by Drew Brokke)—A simple utility to replace tokens in a string with generations from the chance random generator helper
 - [`css-assets`](https://github.com/manojchandrashekar/css-assets#readme) (by Manoj Chandrashekar)—Helps build CSS files and referenced assets.
 - [`doodle-data`](https://github.com/regular/doodle-data#readme) (by Jan Bölsche)—get the data of a doodle.com poll
 - [`emoji.css`](https://github.com/IonicaBizau/emoji.css)—Your website. Emojified. Like FontAwesome for emojis.
 - [`engine-flow-types`](https://github.com/jillix/engine-flow-types#readme) (by jillix)—Low level library providing Engine flow types.
 - [`html-encoder-decoder`](https://github.com/IonicaBizau/html-encoder-decoder)—HTML Encoder / Decoder - Converts characters to their corresponding HTML Entities
 - [`hubot-lgtm`](https://github.com/catops/hubot-lgtm#readme) (by Chris Contolini)—Automatically merge pull requests after contributors have given the thumbs up
 - [`luhnify`](https://github.com/koopero/luhnify#readme) (by Samm Cooper)—Generate random Luhn sequences, such as credit card numbers.
 - [`parse-it`](https://github.com/IonicaBizau/parse-it#readme)—Configurable string templating, without separators.

## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
