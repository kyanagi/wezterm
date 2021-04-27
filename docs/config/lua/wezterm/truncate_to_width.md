# wezterm.truncate_to_width(string, max_width, min_width)

*Since: nightly builds only*

Returns a copy of `string` that is no longer than `max_width` columns
(as measured by [wezterm.column_width](column_width.md)), and, optionally,
no shorter than `min_width` columns, padding out with spaces.

For example, `wezterm.truncate_to_width("hello", 3)` returns `"hel"`,
and `wezterm.truncate_to_width("a", 10, 5)` returns "a    "`.
