<p align="center">
    <h2 align="center" style="letter-spacing:2px;font-weight:700">MONOKAI SMOOTH</h2>
</p>

<p align="center">A theme based on Monokai Vibrant with lighter background and modified colours.</p>

## Disable Italics

If you are not using a font that does not support italics, you can add this to your `settings.json` to disabled them.

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "Monokai Vibrant - No Italics",
      "scope": [
        "comment",
        "string.comment",
        "variable.language",
        "keyword",
        "storage",
        "variable.parameter"
      ],
      "settings": {
        "fontStyle": ""
      }
    }
  ]
}
```
