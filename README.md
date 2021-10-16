# The UQCS Cookbook

A book of recipes curated by the UQCS #food channels. Join us [on Discord](https://discord.uqcs.org) to talk food and lots more with our community.

[View the compiled book](https://github.com/UQComputingSociety/cookbook/releases/latest/download/main.pdf)

[![Build Status](https://github.com/UQComputingSociety/cookbook/actions/workflows/build.yml/badge.svg)](https://github.com/UQComputingSociety/cookbook/actions/workflows/build.yml)

## Contributing

You are only allowed to contribute recipes that you have cooked yourself.

### Recipe format

Copy `recipes/template` to a file in the `recipes` directory with a `.tex` extension. The format we follow is from the [`cuisine` latex package](https://www.ctan.org/tex-archive/macros/latex/contrib/cuisine), and documentation for `cuisine` can be [found here](http://mirror.aarnet.edu.au/pub/CTAN/macros/latex/contrib/cuisine/cuisine.pdf).

List ingredients using `\Ing{ingredient and quantity}` rather than `\ing{quantity}{ingredient}`.

### Submitting a recipe

We use a standard pull request workflow for adding recipes to the project. To create a pull request, fork the repo, make your changes, then follow [these instructions from github](https://help.github.com/articles/creating-a-pull-request-from-a-fork/).

Once your pull request is merged, you'll be able to view the updated cookbook with your recipe.

