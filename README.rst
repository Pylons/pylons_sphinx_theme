Pylons Sphinx Theme
===================

This repository contains Pylons themes for Pylons related projects.
To use a theme in your Sphinx documentation, follow this guide:

1. put this directory as _themes into your docs folder.  Alternatively
   you can also use git submodules to check out the contents there
   or symlink this directory as _themes.

2. add this to your conf.py::

    sys.path.append(os.path.abspath('_themes'))
    html_theme_path = ['_themes']
    html_theme = 'pylons'

The following themes exist:

- **pylons** - the generic Pylons Project documentation theme
- **pyramid** - the specific Pyramid documentation theme
- **pylonsfw** - the specific Pylons Framework documentation theme
