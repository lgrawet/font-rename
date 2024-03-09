# font-rename

Renames fonts to their internal name and unpacks .ttc/.otc files.

This is a fork of [whtsky/font-rename](https://github.com/whtsky/font-rename) to make it run with python >=3.11 and to replace spaces with underscores in font file names.

Install it with `poetry install` and run it with

```bash
font-rename insert/directory/file/path/here
```

## Changelog

### v0.2.0

- Add the option to remove unparsable fonts [#11](https://github.com/whtsky/font-rename/pull/11)
- Add `.otc` support [#9](https://github.com/whtsky/font-rename/pull/9)
- Fix invalid .ttc handling [#9](https://github.com/whtsky/font-rename/pull/9)

### v0.1.0

- Initial Release
