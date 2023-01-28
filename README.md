# `wifi-status`

* Minimal Status bar for Network (`WiFi` & `Wired`) Status using Go

## `To-Do`

- [ ] Implement `dbus` Interface for NetworkManager
	- Ref: *"Notes on D-Bus"*, networkmanagr.dev, https://networkmanager.dev/blog/notes-on-dbus/
- [ ] Subscribe `dbus` Notification and Signal to `i3Blocks` when Network Status is Changed.
	- Ref: [`dbus/_examples/signal.go`](https://github.com/godbus/dbus/blob/master/_examples/signal.go)
	- Ref: [`i3blocks#signal`](https://github.com/vivien/i3blocks#signal)
- [ ] Show Network Information Box when Status is Clicked.
	- Ref: [`i3blocks#click`](https://github.com/vivien/i3blocks#click)

### `Additional To-Dos`

- [ ] Bypassing (or `Auto Log-in`) Captive Portal on `Starbucks`
