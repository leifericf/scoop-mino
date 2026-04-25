# scoop-mino

Scoop bucket for [mino](https://github.com/leifericf/mino), a tiny embeddable Lisp in pure ANSI C.

## Install

```
scoop bucket add mino https://github.com/leifericf/scoop-mino
scoop install mino
```

## How this bucket is updated

Manifests in `bucket/` are kept in sync with `mino` releases by the
`promote-packages` workflow in the [`mino`](https://github.com/leifericf/mino)
repo. Each release of `mino` opens a PR here updating `bucket/mino.json`
to point at the new release zip and SHA256; PRs are reviewed and merged
manually.

## License

MIT
