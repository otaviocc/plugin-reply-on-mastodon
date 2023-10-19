# Reply on Mastodon for Micro.blog

## Overview

This Micro.blog plugin adds a button to your blog, allowing readers to reply to a post on Mastodon. When correctly integrated into your blog theme, it appears for posts that were cross-posted to Mastodon. For posts that weren't cross-posted, the button won't appear.

![Plugin Preview](https://otavio.cc/uploads/2023/plugin-02.png)

Once enabled, the plugin allows you to configure the button's title. By default, it displays "🐘 Reply on Mastodon" because emojis are cool.

![Button Configuration](https://otavio.cc/uploads/2023/plugin-01.png)

## Contributors

This plugin [was born in Micro.blog's help forum](https://help.micro.blog/t/reply-on-mastodon-plugin/2203). The community recognized the need for this integration, investigated the information Micro.blog provides to make it happen, and explored various solutions.

The success of this plugin is attributed to the dedicated contributions of the following individuals (in alphabetical order):

- [Greg](https://micro.blog/gr36)
- [James](https://micro.blog/jrr)
- [Jarrod](https://micro.blog/jarrod)
- [Otávio](https://micro.blog/otaviocc)
- [Pratik](https://micro.blog/pratik)
- [Sven](https://micro.blog/sod)

## Installation

### Manual Integration

Integrating the plugin requires adding the following lines to your blog's template. The code below checks if the plugin is installed and imports it if necessary.

```html
{{ if templates.Exists "partials/reply-on-mastodon.html" }}
{{ partial "reply-on-mastodon.html" . }}
{{ end }}
```

### Automatic Integration

Some themes may already have this plugin integrated by default. In such cases, all you need to do is enable the plugin for your blog.

## Issues and Feedback

We highly value your feedback and encourage you to report any issues you encounter. Please use the GitHub Issues page to submit bug reports or feature requests.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute this software in accordance with the terms of the license.
