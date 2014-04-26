# slackhack

> Manupulate Slack inbound webhooks.

Provides a simple commandline interface for Slack Incoming WebHooks.

## Install
`npm install -g slackhack`

## Configuration
You must create a YAML config file, with the following format:

```yaml
app: <your_app_name>
token: <slack_webhook_token>
channel: <default_channel> #optional
```

Example:

```yaml
app: slackhack
token: frDFFtg56Gdfgg
channel: #random
```

## Usage
Now that `slackhack` is configured and installed globally, run `slackhack` to use the CLI.

If you want to take it for a test run, copy/paste this into the command line:

```bash
slackhack "Hello world!"
```

`slackhack` will look for `slackhack.yml` in the working directory if no config file argument is specified.

For more details, try `slackhack --help`

See the Slack Incoming WebHooks documentation for details of valid input.

## Author

**Kevin Lanni**

* [github/therealklanni](https://github.com/therealklanni)

## License
Copyright (c) 2014 Kevin Lanni, contributors.
Released under the MIT license
