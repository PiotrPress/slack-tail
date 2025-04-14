# Slack Tail

A simple command line tool to tail a file and send the output to a [Slack](https://slack.com) channel.

## Usage

```shell
$ php bin/tail <file> <url>
```

Where `<file>` is the path to the file you want to tail and `<url>` is the [Slack webhook](https://api.slack.com/messaging/webhooks) URL.

## Example

```shell
$ php bin/tail /var/log/apache2/access.log https://hooks.slack.com/services/T00000000/B00000000/XXXXXXXXXXXXXXXXXXXXXXXX
```

## Requirements

PHP >= `7.4` version.

## License

[MIT](license.txt)