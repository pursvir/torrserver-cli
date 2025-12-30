A simple CLI for interacting with [TorrServer](https://github.com/YouROK/TorrServer) instances, written in Python. Inspired by [peerflix](https://github.com/mafintosh/peerflix).

Install script dependencies:

```sh
pip install requests parse-torrent-title
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

- `"Empty playlist!"`, `"Something went wrong!"`

TorrServer may sometimes respond with empty messages. Just run the same command after a few seconds.
