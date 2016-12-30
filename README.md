# Sandscape plugins

This repository contains Sandscape plugins.  Sandscape plugins are used by
[Sandscape][ss].

# Naming plugins

Sandscape plugins which configure Jenkins core settings should be named
`core-*`.  Sandscape plugins which configure Jenkins plugins should have the
same name as the Jenkins plugin ID.  For example, the [GitHub Authentication
Plugin][gh-oath] would have a Sandscape plugin named `github-oauth` and have a
file `github-oauth.groovy`.

Sandscape plugins configuring Jenkins plugins must list the Jenkins plugin
version in which that plugin was tested.

# Plugins list

Sandscape plugins for configuring Jenkins core settings: `<none yet>`

Sandscape plugins for configuring Jenkins plugins: `<none yet>`

[gh-oath]: https://wiki.jenkins-ci.org/display/JENKINS/GitHub+OAuth+Plugin
[docs]:
[ss]: https://github.com/sandscape/sandscape
