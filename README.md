# [ProjectEuler100 Twitter Bot](https://twitter.com/ProjectEuler100)

<strong>I help developers who participate in
[#ProjectEuler100](https://twitter.com/search?q=%23ProjectEuler100&src=hashtag_click)
to engage on Twitter.</strong>

[![License (3-Clause BSD)](https://img.shields.io/badge/license-BSD%203--Clause-blue.svg?style=flat-square)](http://opensource.org/licenses/BSD-3-Clause)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

<p>
  <a href="https://twitter.com/intent/follow?screen_name=ProjectEuler100">
    <img src="https://img.shields.io/twitter/follow/ProjectEuler100.svg?style=social"
      alt="follow on Twitter"></a>
</p>

![Logo](https://i.imgur.com/fDPhwZL.png)

## API

- It encourages developers who participate in #ProjectEuler100 challenge hosted by [@freeCodeCamp](https://twitter.com/freeCodeCamp)
- The API consists of "favorite" and "retweet" a tweet at an interval of every 30 minutes

---

## Contributing

This bot creates tweets and streams by connecting to the
[Twitter API](https://developer.twitter.com/en/docs) via the `twit`
npm package. Please refer to the `twit`
[documentation](https://github.com/ttezel/twit) to make substantial
changes.

You can help by:

- Solving existing issues

For any of the above, please create an issue so that it can be addressed. New to GitHub issues? You can familiarize yourself with
them using GitHub's
[guide](https://help.github.com/articles/creating-a-pull-request/).

## How to setup the bot?

- You will need your _own_ Twitter account for testing, since the bot tweets from this account. Generate your Twitter API keys by [creating a new app](https://apps.twitter.com/app/new).
- Create an `.env` file and add in your API keys and Twitter handle, like so:

```
TWITTER_CONSUMER_KEY=xxxxxxxxxxxxxxxxxxxxdMhxg
TWITTER_CONSUMER_SECRET=xxxxxxxxxxxxxxxxxxxxkFNNj1H107PFv1mvWwEM6CZH0fjymV
TWITTER_ACCESS_TOKEN=xxxxxxxxx-xxxxxxxxxxxxxxxxxxxxecKpi90bFhdsGG2N7iII
TWITTER_ACCESS_TOKEN_SECRET=xxxxxxxxxxxxxxxxxxxxZAU8wNKAPU8Qz2c0PhOo43cGO
```

---

## License

BSD 3-Clause License

Copyright (c) 2020, freeCodeCamp. All rights reserved.
