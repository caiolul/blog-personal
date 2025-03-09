+++
author = "Hugo Authors, Asdf Authors, NeoHsu" 
title = "Tutorial: Install Hugo by Asdf" 
date = "2025-01-14"
description = "Install Hugo by Asdf" 
tags = [ "markdown", "text", ]
categories = [ "tutorials", "personal", ]
+++

## Introduction 

This is a guide to install Hugo by Asdf.


## Install Asdf

First, install Asdf by following the instructions on the [official website](https://asdf-vm.com/#/core-manage-asdf-vm).

## Install Hugo

After installing Asdf, run the following command to install Hugo:

```bash
asdf plugin add hugo
# or
asdf plugin add hugo https://github.com/NeoHsu/asdf-hugo.git
```

Then, install the desired version of Hugo:

```bash
# Show all installable versions
asdf list-all hugo

# Install specific version
asdf install hugo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hugo latest

# Now hugo commands are available
hugo version
```


Extended for builds for Sass/SCSS:

```bash
# Install extended hugo version
asdf install hugo extended_0.85.0

# Now you can manage it like you're used to
asdf global hugo extended_0.85.0
```

## Conclusion

Now you have Hugo installed by Asdf. Enjoy!
