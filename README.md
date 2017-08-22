# Dokku Discord

Dokku Discord is a plugin for [Dokku](https://github.com/progrium/dokku) that notifies [Discord](http://www.discordapp.com) of deployments.

## Installation

```sh
# dokku 0.3.26
$ git clone https://github.com/gu3st/dokku-discord /var/lib/dokku/plugins/discord

# dokku 0.4+
$ dokku plugin:install https://github.com/gu3st/dokku-discord.git
```

## Commands

```sh
$ dokku help
    discord:set <app> <webhook_url>                   Set Discord WebHook URL
    discord:clear <app>                               Clears Discord WebHook URL
    discord:get <app>                                 Display Discord WebHook URL
```

To get **WebHook URL** you need to create a new Webhook URL

## License

The MIT License (MIT)

Copyright (c) 2015 ribot

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
