# Cyberpunk Theme for Pi

A dark Pi theme prototype with neon pink, cyan, and yellow on dark blue surfaces. It colors the interface, Markdown, syntax, and HTML exports; the terminal's background color remains controlled by the terminal itself.

## Try it out

From the project directory:

```sh
pi --approve --use-theme cyberpunk
```

`--approve` allows Pi to load the project theme from `.pi/themes/cyberpunk.json` for this invocation. Alternatively, once you have trusted the project in a running Pi session, select the **cyberpunk** theme via `/settings`. Run `/reload` after making changes to the project theme.

To use the theme outside this project, copy the file to `~/.pi/agent/themes/cyberpunk.json`, then start Pi with `pi --use-theme cyberpunk`. If your terminal background is very light, a dark terminal profile is recommended.
