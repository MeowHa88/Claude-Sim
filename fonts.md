# Font Dependencies

Claude-Sim prioritizes comfortable Chinese reading in Obsidian while keeping Codex UI layout stable with system UI fonts and code in a non-serif monospace stack.

## Preferred Obsidian UI/Text Fonts

```text
LXGW WenKai Screen
Noto Serif SC
Noto Serif CJK SC
Source Han Serif SC
PingFang SC
Hiragino Sans GB
Microsoft YaHei
```

Recommended installed fonts:

- `LXGW WenKai Screen`: primary Chinese reading font.
- `Noto Serif SC`: serif Chinese fallback, already suitable for long text.
- `Source Han Serif SC`: optional fallback.

If the preferred fonts are missing, the theme falls back to macOS/system Chinese fonts.

## Code Font Stack

```text
ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Monaco, Consolas, monospace
```

This keeps code in a non-serif monospace font.

## Codex UI Font Stack

```text
-apple-system, BlinkMacSystemFont, 'SF Pro Text', 'PingFang SC', 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif
```

Codex uses a system sans-serif UI stack to avoid layout issues in settings pages and status/progress output.
