# Contributing Guide to PHP Resources

We love contributors and people willing to help.

## How Can You Help?

* Report issues
* Fix typos and grammar
* Add new content
* Improve existing chapters

## Contributing Procedure

Below is described procedure for contributing to this repository in particular
and some extra information about it.

* Fork this repository over GitHub
* Create a separate branch for instance `patch-1` so you will not need to rebase
  your fork if your master branch is merged

  ```bash
  git clone git@github.com:your_username/php-resources
  cd php-resources
  git checkout -b patch-1
  ```
* Make changes, commit them and push to your fork

  ```bash
  git add .
  git commit -m "Fix typo in the FAQ"
  git push origin patch-1
  ```
* Open a pull request

## Style Guide

* This repository uses [Markdown](https://daringfireball.net/projects/markdown/)
  syntax and follows
  [cirosantilli/markdown-style-guide](http://www.cirosantilli.com/markdown-style-guide/)
  style guide.

* Code examples follow [PSR-1](http://www.php-fig.org/psr/psr-2/),
  [PSR-2](http://www.php-fig.org/psr/psr-2/) and
  [extended code style guide proposal](https://github.com/php-fig/fig-standards/blob/master/proposed/extended-coding-style-guide.md).

* The preferred spelling of English words is the [American
  English](https://en.wikipedia.org/wiki/American_English) (e.g. behavior, not
  behaviour).

* Titles have [capitalized](https://en.wikipedia.org/wiki/Letter_case#Headings_and_publication_titles)
  certain words such as nouns, pronouns, adjectives, verbs, adverbs, and subordinate
  conjunctions.

* Use gender-neutral language (instead of *he* or *she* use *they*, *them*,
  *their*, *theirs*, *themselves*).

* Use second person point of view (instead of *I* and *we*, use *you*). Avoid
  [nosism](https://en.wikipedia.org/wiki/Nosism).

## Images

Some images are created with the [draw.io][draw.io] tool. They are also located
in a [separate repository](https://github.com/wwphp-fb/php-resources-assets).

## YAML Front Matter

Contents include the YAML front matter blocks with the following parameters to
define extra content information:

* `permalink` - URL path of the content
* `title`
* `image` - image used for open graph
* `updated` - last contextual change date
* `redirect_from` - 301 redirects of previous URLs

## GitHub Issues Labels

Labels are used to organize issues and pull requests into manageable categories.
The following labels are used:

* **duplicate** - Attached when the same issue or pull request already exists.
* **easy pick** - Requires simple work.
* **enhancement** - New feature.
* **faq** - Attached for FAQ section content.
* **hacktoberfest** - Attached for open source [Hacktoberfest] event.
* **invalid** - Attached when
* **needs review** - Attached when further review is required.
* **new content** - For new articles or new FAQs.
* **question** - Attached for questions or discussions.
* **wontfix** - Attached when decided that issue will not be fixed.

## License

By contributing to this repository you agree to share knowledge under the
[Creative Commons Attribution-ShareAlike 4.0 International][license] and code
under the [public domain][license].

## Release Process

*(For repository maintainers)*

This repository follows [semantic versioning](http://semver.org). When new changes
are added, a new version (e.g. `1.x.y`) is released by the following release
process:

1. Changelog update:

  Create an entry in [CHANGELOG.md](CHANGELOG.md) describing all the changes from
  previous release.

2. Tag new release:

  Tag a new version on GitHub, and attach necessary binary file(s).

3. Update the [git module](https://github.com/wwphp-fb/wwphp-fb.github.io) for
  the GitHub page.


[draw.io]: https://www.draw.io
[license]: https://github.com/wwphp-fb/php-resources/blob/master/LICENSE
[Hacktoberfest]: https://hacktoberfest.digitalocean.com/
