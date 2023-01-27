# Royal Velvet Obsidian Theme

A theme for [Obsidian](https://obsidian.md/), inspired by the beautiful colours of [Royal Velvet Obsidian](https://duckduckgo.com/?t=ffab&q=Mexican+Royal+Velvet+Obsidian&iax=images&ia=images) and the distinct colours used in programming syntax highlighting themes.

![](royal-velvet.png)

## Emoji in headings

If you use emoji in headings, you will need to add a plugin to make these display in the right colour in reading mode. Install and enable the [Dynamic Highlights](https://github.com/nothingislost/obsidian-dynamic-highlights) plugin, and import the following code in that plugin's settings:

```json
{
  "emoji": {
    "class": "emoji",
    "color": "",
    "regex": true,
    "query": "\\p{Extended_Pictographic}",
    "mark": ["match", "start", "end"],
    "css": ".emoji { color:black;  -webkit-text-fill-color: black; }"
  }
}
```

## Customization (Experimental)

Customization options are made available by [The Style Settings Plugin](https://github.com/mgmeyers/obsidian-style-settings). As this feature is experimental, it's possible that it will undergo significant changes in the future. Feedback is appreciated.

### Inline Document Title Color

The inline document title's color can be set as any of the following;

- **Disabled** - uses normal text color
- **Custom color** - based on the hue of your configured accent color
- **Rainbow**
- **Same as a specific heading level** (default)

## Feedback

If you have any issues or suggestions, please [submit an issue](https://github.com/caro401/royal-velvet/issues/new) or raise a [pull request](https://github.com/caro401/royal-velvet/pulls/).

I don't use many plugins or advanced features of Obsidian, so there's definitely some usecases that won't look good - please let me know!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U7BUEZ6)
