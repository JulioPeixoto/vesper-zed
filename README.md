# Vesper for Zed

Peppermint and orange flavored dark theme for [Zed](https://zed.dev), ported from
[Vesper](https://github.com/raunofreiberg/vesper) for VS Code by Rauno Freiberg.

## Palette

| Role               | Color     |
| ------------------ | --------- |
| Background         | `#101010` |
| Foreground         | `#FFFFFF` |
| Muted / keywords   | `#A0A0A0` |
| Accent / functions | `#FFC799` |
| Strings            | `#99FFE4` |
| Errors             | `#FF8080` |
| Comments           | `#8B8B8B94` |

## Install (dev extension)

1. Clone this repo.
2. In Zed, open the command palette and run `zed: install dev extension`.
3. Select the cloned folder.
4. Run `theme selector: toggle` and choose **Vesper**.

Or copy `themes/vesper.json` into `~/.config/zed/themes/` (on Windows,
`%APPDATA%\Zed\themes\`) and restart Zed.

## Notes

The original theme doesn't define terminal colors, so the ANSI palette here is built
from Vesper's own colors (blue maps to gray, magenta to orange).

## License

MIT. The original Vesper theme is MIT licensed by Rauno Freiberg.
