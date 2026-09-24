# scoop-snyvi

The [Scoop](https://scoop.sh) bucket for [snyvi](https://github.com/snymrova/snyvi),
a fast, beautiful viewer for the documents your agents produce.

```
scoop bucket add snyvi https://github.com/snymrova/scoop-snyvi
scoop install snyvi
snyvi init-claude --auto
```

`scoop update snyvi` updates it, stopping the daemon and the window first.
`scoop uninstall snyvi` removes it and leaves your documents.

`bucket/snyvi.json` is written by snyvi's release workflow
(`packaging/scoop.sh` there) from the checksum published beside each
release's Windows zip, so the bucket never names a version that has not
shipped. Nothing is edited here by hand.
