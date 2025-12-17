A simple CLI for interacting with [TorrServer](https://github.com/YouROK/TorrServer) instances, written in Python.

The only external module used is `requests`:

```sh
pip install requests
```

Documentation:

```sh
torrctl --help
```

Example workflow:

```sh
mpv $(torrctl add -u "YOUR_MAGNET_LINK")
```

# Troubleshooting

- `"Empty playlist!"`

TorrServer may sometimes respond with empty messages. Just run the same command after a few seconds.
