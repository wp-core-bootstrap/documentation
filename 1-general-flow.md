# General Flow [![Edit in GitHub](https://img.shields.io/badge/Edit_in_GitHub--gray.svg?style=social)](https://github.com/wp-core-bootstrap/documentation/edit/master/1-general-flow.md)

The Bootstrap component is responsible for abstracting away all platform/environment idiosyncrasies so that the actual Core logic does not have to deal with these differences anymore. It locates all the moving pieces, defines all needed constants, and sets up the configuration.

The bootstrap component is the first point of contact of a web request with the WordPress platform.

Here's a simplified view of how a request is being handled by WordPress:

![Simplified overview](https://rawgit.com/wp-core-bootstrap/documentation/master/assets/images/simplified-overview.svg)
