# wl-copy

> Wayland clipboard manipulation tool.
> See also: `wl-paste`.
> More information: <https://github.com/bugaevc/wl-clipboard>.

- Copy text to the clipboard:

`wl-copy {{text}}`

- Copy the output of a command to the clipboard:

`{{command}} | wl-copy`

- Copy for only one paste and then clear it:

`wl-copy --paste-once`

- Clear the clipboard:

`wl-copy --clear`
