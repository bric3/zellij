<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/zellij-org/zellij/main/assets/logo.png" alt="logo" width="200">
  <br>
  Zellij
  <br>
  <br>
</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/zellij-org/zellij/main/assets/demo.gif" alt="demo">
</p>

<p align="center">
  <a href="https://discord.gg/CrUAFH3"><img alt="Discord Chat" src="https://img.shields.io/discord/771367133715628073"></a>
</p>


# What is this?

[Zellij](https://en.wikipedia.org/wiki/Zellij) is a workspace aimed at developers, ops-oriented people and anyone who loves the terminal.
At its core, it is a terminal multiplexer (similar to [tmux](https://github.com/tmux/tmux) and [screen](https://www.gnu.org/software/screen/)), but this is merely its infrastructure layer.

Zellij includes a [layout system](https://zellij.dev/documentation/layouts.html), and a [plugin system](https://zellij.dev/documentation/plugins.html) allowing one to create plugins in any language that compiles to WebAssembly.

For more details about our future plans, read about upcoming features in our [roadmap](#roadmap).

Zellij was initially called "Mosaic".

## How do I install it?
You can install it through `cargo`:

```
cargo install zellij
```

Or you can download a prebuilt binary from our [Releases](https://github.com/zellij-org/zellij/releases).

## How do I hack on it? (Contributing)
* Clone the project
* Install cargo-make with `cargo install --force cargo-make`
* In the project folder, for debug builds run: `cargo make run`

For more build commands, see [`Contributing.md`](CONTRIBUTING.md).

## Configuration
For configuring Zellij, please see the [Configuration documentation](https://zellij.dev/documentation/configuration.html).

## What is the current status of the project?

Zellij should be ready for everyday use, but it's still classified as a beta. This means that there might be a rare crash or wrong behaviour here and there, but that once found it should be fixed rather quickly. If this happens to you, we would be very happy if you could open an issue and tell us how to reproduce it as best you can.

## How do I get involved?

Zellij is a labour of love built by an enthusiastic team of volunteers. We eagerly welcome anyone who would like to join us, regardless of experience level.

To get started, you can:
1. Take a look at the "Issues" in this repository - especially those marked "Good first issue". Those with the "Help Wanted" tag probably don't have anyone else working on them.
2. Drop by our [chat](https://discord.gg/CrUAFH3) and ask what you can work on, or how to get started.
3. Open an issue with your idea(s) for the project or tell us about them in our chat.

And most importantly, please read our [code of conduct](CODE_OF_CONDUCT.md).

## Roadmap
This section contains an ever-changing list of the major features that are either currently being worked on, or planned for the near future.
  * **A web client/server** - Connect to Zellij through the browser instead of opening a terminal window. Either on a local or remote machine.
  * **Share sessions with others** - See the focused window and cursor of other users, work on a problem or a code base together in real time.
  * **Support for multiple terminal windows across screens** - Transfer panes across different windows and screens by having them all belong to the same session.
  * **Smart layouts** - expand the current layout system so that it rearranges and hides panes intelligently when new ones are added or the window size is changed.

## License

MIT
