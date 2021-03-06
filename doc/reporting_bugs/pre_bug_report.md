Before reporting a bug, lets make sure everything is right with your setup.

When reporting bugs, remember that Homebrew-Cask is an independent project from Homebrew. Do your best to direct bug reports to the appropriate project. If your command started with `brew cask`, bring the bug to us first.

Start by searching for your issue before posting a new one. If you find an open issue and have any new information not reported in the original, please add your insights. If you find a closed issue, try the solutions there. If the issue is still not solved, open a new one with your new information and a link back to the old related issue.

If you did not find your particular bug, before reporting it make sure you have the latest versions of Homebrew, Homebrew-Cask, and all Taps by running the following command, as well as fixing some other issues:

```bash
$ brew update; brew cleanup; brew cask cleanup;
$ brew uninstall --force brew-cask; brew update
$ brew untap phinze/cask; brew untap caskroom/cask; brew update
```

Retry your failing command. If the issue persists, [go back](../../README.md#reporting-bugs) and pick `My problem isn’t listed` to fill our bug report template.
