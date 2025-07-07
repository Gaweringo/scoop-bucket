# Scoop Bucket

[![Tests](https://github.com/gaweringo/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/gaweringo/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/gaweringo/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/gaweringo/scoop-bucket/actions/workflows/excavator.yml)

Template bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I use this template?

8. If you'd like your bucket to be indexed on `https://scoop.sh`, add the
   topic `scoop-bucket` to your repository.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add gaweringo https://github.com/gaweringo/scoop-bucket
scoop install gaweringo/<manifestname>
```

### Available Manifests
- [ghdl](./bucket/ghdl.json)
- [nvc](./bucket/nvc.json)
- [raddbg](./bucket/raddbg.json)
- [tinymist](./bucket/tinymist.json)
- [uvconverter](./bucket/uvconverter.json)
- [vhdl_ls](./bucket/vhdl_ls.json)
- [gtkwave](./bucket/gtkwave.json)
- [vhdl_lang](./bucket/vhdl_lang.json)
- [surfer](./bucket/surfer.json)
- [repgrep](./bucket/repgrep.json)

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
