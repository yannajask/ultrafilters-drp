# Fall 2025 DRP Presentation

I refuse to pay $10/month for Overleaf to be able to compile a Beamer presentation, so I set up this repository for us to be able to collaborate on our presentation without having to pay for a subscription.

## Getting Started

I'll assume that you know how to use Git and some basic version control, as well as having VSCode installed.

### Installing TeX

We need to be able to render TeX on our computers. The easiest way to do this is installing MacTeX via Homebrew. If you dont have [Homebrew](https://brew.sh/) installed, you can open a Terminal and run the command:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

After Homebrew is installed, you can install MacTex by running:

```
brew install --cask mactex-no-gui
```

These commands might ask for your computer password - it's safe to put these in. The MacTex package is pretty large so you may have to wait a few minutes after putting in your password (it might look frozen). Once it's installed, you can restart your terminal and check it was successful by running `which latexmk`.

If you accidentally exited installation before it was complete, you might have a half installed package. Just do `brew uninstall mactex-no-gui` and run the command above again.

After you've successfully installed MacTex, you should install the LaTeX Workshop extension by James Yu on VSCode.

### Updating the Presentation

To copy this repository, run the command:

```
https://github.com/yannajask/ultrafilters-drp.git
```

This will clone this repository locally onto your computer. If you open the repository in VSCode and the `template.tex` file, then you should be able to compile the presentation as a pdf within VSCode.

Since we will be working on the same file together, my suggestion is that we should both make our own branches and work on them independently. This way we don't accidentally overwrite each other's work.

