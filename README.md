# sg-hugo-theme
The Hugo theme for https://synapsegarden.net.

# Contributing

Fork this repo into your Github account.  If you want to work with the theme,
then fork that, too.  It is a Git submodule in `themes/sg`.

SynapseGarden runs on [Dash](https://github.com/synapse-garden/dash), a
batteries-included framework for web apps using the
[Mindfork](https://github.com/synapse-garden/mindfork) engine.  To contribute
to Dash or Mindfork, please visit those repositories.

```bash
git clone --recursive https://github.com/synapse-garden/synapsegarden.net
cd synapsegarden.net
# Add your fork as a remote
git remote rename origin upstream
git remote add origin git@github.com:$USER/synapsegarden.net
# Optionally:
cd themes/sg
git remote rename origin upstream
git remote add origin git@github.com:$USER/sg-hugo-theme
# Or to work on Dash:
cd static/dash
# Etc.
```

When you have something you like, push it to your repository and
[open a pull request](https://help.github.com/articles/using-pull-requests/).
