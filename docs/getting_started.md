All you need to get started building Textual apps.

## Requirements

Textual requires Python 3.7 or later (if you have a choice, pick the most recent Python). Textual runs on Linux, macOS, Windows and probably any OS where Python also runs.

!!! info inline end "Your platform"

    ### :fontawesome-brands-linux: Linux (all distros)

    All Linux distros come with a terminal emulator that can run Textual apps.

    ### :material-apple: macOS

    The default terminal app is limited to 256 colors. We recommend installing a newer terminal such as [iterm2](https://iterm2.com/), [Kitty](https://sw.kovidgoyal.net/kitty/), or [WezTerm](https://wezfurlong.org/wezterm/).

    ### :material-microsoft-windows: Windows

    The new [Windows Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=en-gb&gl=GB) runs Textual apps beautifully.

## Installation

You can install Textual via PyPI.

If you plan on developing Textual apps, then you should install `textual[dev]`. The `[dev]` part installs a few extra dependencies for development.

```
pip install "textual[dev]==0.2.0"
```

If you only plan on _running_ Textual apps, then you can drop the `[dev]` part:

```
pip install textual==0.2.0
```

## Demo

Once you have Textual installed, run the following to get an impression of what it can do:

```bash
python -m textual
```

If Textual is installed you should see the following:

```{.textual path="src/textual/demo.py" columns="127" lines="53" press="enter,_,_,_,_,_,_,tab,w,i,l,l"}
```

## Examples


The Textual repository comes with a number of example apps. To try out the examples, first clone the Textual repository:

=== "HTTPS"

    ```bash
    git clone https://github.com/Textualize/textual.git
    ```

=== "SSH"

    ```bash
    git clone git@github.com:Textualize/textual.git
    ```

=== "GitHub CLI"

    ```bash
    gh repo clone Textualize/textual
    ```


With the repository cloned, navigate to the `/examples/` directory where you fill find a number of Python files you can run from the command line:

```bash
cd textual/examples/
python code_browser.py ../
```


## Textual CLI

If you installed the dev dependencies you have access to the `textual` CLI command. There are a number of sub-commands which will aid you in building Textual apps.

```bash
textual --help
```

See [devtools](guide/devtools.md) for more about the `textual` command.

## Need help?

See the [help](./help.md) page for how to get help with Textual, or to report bugs.
