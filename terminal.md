```bash local wezterm = require("wezterm")

return {

	window_decorations = "RESIZE",
	color_scheme = "Batman",
	font = wezterm.font_with_fallback({ "JetBrains Mono", { family = "Symbols Nerd Font Mono", scale = 0.75 } }),
	use_cap_height_to_scale_fallback_fonts = true,
	font_size = 13.3,
	scrollback_lines = 5000,
	hide_tab_bar_if_only_one_tab = true,
}
```

# path name `.wezterm.lua`
