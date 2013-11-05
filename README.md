# github-monitor [![Build Status](https://travis-ci.org/neoziro/github-monitor.png?branch=master)](https://travis-ci.org/neoziro/github-monitor)

Monitor Github commit statuses.

## Example

```sh
github-monitor -t my-github-token -r neoziro/github-monitor
```

## Usage

```
  Usage: github-monitor [options]

  Options:

    -h, --help                 output usage information
    -V, --version              output the version number
    -t, --token <token>        GitHub access token
    -r, --references <values>  Monitored references (ex: neoziro/github-monitor#master,neoziro/hulkster#master)
    -p, --port [port]          HTTP listening port
    -R, --refresh [time]       Refresh time in seconds
    -T, --template [template]  Template to use
```

## License

MIT