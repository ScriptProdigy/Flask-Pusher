Changelog
=========
1.0.1
 * Monkey patch `pusher.json` module to use `flask.json`

1.0
 * `pusher>=1.0` support
 * Custom `JSONEncoder` does not work with `pusher==1.0`

0.4.1
 * Fix dependency version: `pusher<1.0`

0.4
 * Batch auth support
 * Configurable url prefix and authentication path

0.3
 * Webhooks support
 * JSONP authentication support with Flask-Jsonpify

0.2
---
 * Authentication support

0.1
---
 * Initial version
 * Flask app binding to pusher client
