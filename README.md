# FoamFactory Taiga Front Distribution

**IMPORTANT**: This is a special version of https://github.com/taigaio/taiga-front-dist designed to be used by the FoamFactory project. It has special commits that are only relevant to FoamFactory and should **never** be merged back upstream.

This repo is a compiled versión of https://github.com/FoamFactory/taiga-front

## Installation ##

* Clone the repo
* Expose the `dist` directory under a static file web server
* Rename dist/js/conf.example.json to conf.js if you want to change settings

More information about the different installation methods (production, development, vagrant, docker...) can be found here http://taigaio.github.io/taiga-doc/dist/#_installation_guide.


## For Devs ##

To regenerate branches ```master``` and ```stable```

```
git checkout master; node dist.js master
git checkout stable; node dist.js stable
```

Note that currently, `master` does not work on `mustafar`.
