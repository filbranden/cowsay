# cowsay

Cowsay is a configurable talking cow, written in Perl.  It operates
much as the figlet program does, and is written in the same spirit
of silliness.

## cowsay-apj

This project you're looking at is [Andrew Janke](https://github.com/apjanke/)'s fork of Cowsay. It is an exercise in applying open source development and deployment practices to a small project. My hope is that this becomes the canonical modern fork of Cowsay.

This fork is called "cowsay-apj" where needed to distinguish it from the original Cowsay project. Otherwise, the program and project itself are still called "Cowsay".

The bulk of Cowsay's functionality is from Tony Monroe's original project. The cowsay-apj fork primarily provides maintenance, hosting, and deployment support, plus support for random cow selection and pluggable third-party cow collections.

## Installation

Cowsay uses the standard `make`-based Unix program installation:

```bash
make install
```

or:

```bash
make install prefix=/path/to/installation/prefix
```

### Installation using Homebrew

On Mac, you can also install Cowsay using Homebrew:

```bash
brew install cowsay-org/cowsay/cowsay-apj
```

## License

Cowsay is licensed under the GPLv3. See [LICENSE.txt](LICENSE.txt) for details.

## History

Cowsay is actually a pretty old program. It was originally written by Tony Monroe and was first released in 1999, but was in use by Monroe for quite a while before that.

The first major version of Cowsay had one cow and one message template: $foo is $verb $bar.  Not very flexible, but people managed to do pretty interesting things with it.  The second major version scrapped many of the limitations of the first, by allowing arbitrary messages, multiple cowfiles, and even support for cows talking in figlet.  The third version was a rewrite of the second into Perl 5, whereupon the code got a lot smaller and more manageable. :-)

As of 2016, Monroe was no longer interested in maintaining Cowsay, and posted a [final 3.04 version on GitHub](https://github.com/tnalpgge/rank-amateur-cowsay) to make it available to other developers. Andrew Janke, a Cowsay fan, forked the project to provide ongoing maintenance and hosting for Cowsay, and as an exercise in FLOSS development processes.

## Requirements

Cowsay requires Perl 5.005_03 or later.

## Other cow collections

You can find collections of cowfiles for use with Cowsay in various third-party projects.
Here's a list of some that look interesting:

* [paulkaefer/cowsay-files](https://github.com/paulkaefer/cowsay-files/)
* [bkendzior/cowfiles](https://github.com/bkendzior/cowfiles)

See the documentation in each for instructions on how to install them.
You can also use Cowsay's `etc/cowsay/cowpath.d` mechanism to make Cowsay aware of them at a system-wide level, so users don't have to configure their `$COWPATH` variables themselves.

## Enjoy

Enjoy Cowsay for what it was meant to be: simple and silly.
