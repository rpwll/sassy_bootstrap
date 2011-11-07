# Bootstrap.sass #

Bootstrap is Twitter's toolkit for kickstarting CSS for websites, apps, and more. It includes base CSS styles for typography, forms, buttons, tables, grids, navigation, alerts, and more.

This particular version of Bootstrap includes a port to SCSS by [Rhys Powell][rpowell].

[rpowell]: http://rpowell.me/

To get started -- checkout http://twitter.github.com/bootstrap!


## Usage ##

You can use Twitter Bootstrap in one of three ways: just drop the compiled CSS into any new project and start cranking, run LESS on your site and compile on the fly like a boss.

Here's what the LESS version looks like:

``` html
<link rel="stylesheet/less" type="text/css" href="lib/less/bootstrap.less">
<script src="less.js" type="text/javascript"></script>
```

Or if you prefer, the standard css way:

``` html
<link rel="stylesheet" type="text/css" href="bootstrap.css">
```

For more info, refer to the docs!


## Versioning ##

For transparency and insight into our release cycle, and for striving to maintain backwards compatibility, Bootstrap will be maintained under the Semantic Versioning guidelines as much as possible.

Releases will be numbered with the follow format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backwards compatibility bumps the major
* New additions without breaking backwards compatibility bumps the minor
* Bug fixes and misc changes bump the patch

For more information on SemVer, please visit http://semver.org/.


## Bug tracker ##

Have a bug? Please create an issue here on GitHub!

https://github.com/FrogBot/bootstrap/issues


## Twitter account ##

Keep up to date on announcements and more by following Bootstrap on Twitter, <a href="http://twitter.com/TwBootstrap">@TwBootstrap</a>. Updates to the core Bootstrap CSS will find their way here fairly soon after release.


## Mailing list ##

Have a question? Ask on our mailing list!

twitter-bootstrap@googlegroups.com

http://groups.google.com/group/twitter-bootstrap


## Developers ##

We have included a makefile with convenience methods for working with the bootstrap library.

+ **build** - `make build`
This will run the less compiler on the bootstrap lib and generate a bootstrap.css and bootstrap.min.css file.
The lessc compiler is required for this command to run.

+ **watch** - `make watch`
This is a convenience method for watching your less files and automatically building them whenever you save.
Watchr is required for this command to run.

For the SCSS files, a Rakefile is included, intended to be used with the ruby `rake` program. To build the SCSS files simply run `rake build_scss`.


## Original Authors ##

**Mark Otto**

+ http://twitter.com/mdo
+ http://github.com/markdotto

**Jacob Thornton**

+ http://twitter.com/fat
+ http://github.com/fat


## License ##

Copyright 2011 Twitter, Inc.

Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0