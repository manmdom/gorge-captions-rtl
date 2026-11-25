# Gorge Captions RTL

ASS/SRT caption skill adapted for Arabic. It wraps every cue in Unicode RTL isolation,
keeps letters joined (no isolated/reversed glyphs), and restores colours explicitly
instead of using `{\r}` resets that broke shaping.

Upstream ideas: [VideoReels Remotion Arabic text guide](https://github.com/manmdom/VideoReels/blob/main/Videos97/.opencode/skills/remotion-markup/arabic-text.md).

Use: `python3 scripts/make_subs.py timing.json -o subs.ass --srt subs.srt --font "Noto Naskh Arabic"`.
