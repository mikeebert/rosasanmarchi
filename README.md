###The professional site for Rosa SanMarchi
Viewable at [rosasanmarchi.github.io](http://rosasanmarchi.github.io)


Site built using [Nanoc](http://nanoc.ws). 

####SETUP:

Clone repo and `bundle install`

Source files are in the 'content' and 'layout' directories. Run `guard` to autocompile to 'output'

Run `nanoc view` to view compiled changes at localhost:3000 

The 'output' directory is a sub repo pushed to rosasanmarchi/rosasanmarchi.github.io:master

- Custom compile rules have been added to `Rules` for the `stylesheets`, `scrips`, `img` and `public` directories.

**NOTE**: The files in the `output/fonts/` are managed manually because the lightgallery plugin requires four font files that have the same base name but different extensions. Nanoc will not properly compile four files of the same name.

- The photo gallery was originally built using [Backbone](http://backbonejs.org) but was switched to lightgallery. See commit history and relevant files in content/scripts and view/layouts

####Deploy
- Deployments are handled via [git-ftp](https://github.com/git-ftp/git-ftp)
