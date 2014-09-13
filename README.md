####The professional site for Rosa SanMarchi
Viewable at [rosasanmarchi.github.io](http://rosasanmarchi.github.io)

Site built using [Nanoc](http://nanoc.ws)

Clone repo and `bundle install`

Source files are in the 'content' and 'layout' directories. Run `guard` to
autocompile to 'output'

Run `nanoc view` to view compiled changes at localhost:3000 

The 'output' directory is a sub repo pushed to rosasanmarchi/rosasanmarchi.github.io:master

- Custom compile rules have been added to `Rules` for scripts and
stylesheets.

- The photo gallery is build using [Backbone](http://backbonejs.org) -
relevant files are in content/scripts and view/layouts

####Deploy
- Deployments are handled via [git-ftp](https://github.com/git-ftp/git-ftp)
