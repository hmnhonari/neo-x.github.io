# Chandar-lab Website

Jekyll setup and content for https://chandar-lab.github.io/

## Maintenance

If there are updates to people, publications, or news you can in most cases easily update this information yourself.
If you need help you can contact the current maintainer. If you don't speak French and need to provide French information,
just create a PR with the English content and contact the French maintainer to help you.

### Publications

When a publication is added or changed:

1. Update [`_data/publications.yaml`](https://github.com/chandar-lab/chandar-lab.github.io/edit/master/_data/publications.yaml)
2. Create a pull request and ask the current maintainer to review.

### News

When the news section needs to be changed:

1. Update [`_data/people.yaml`](https://github.com/chandar-lab/chandar-lab.github.io/edit/master/_data/news.yaml)
2. Create a pull request and ask the current maintainer to review.

### People

_Note: Only the maintainer is expected to do this._

#### When someone joins the group:

1. Add them to [`_data/people.yaml`](https://github.com/chandar-lab/chandar-lab.github.io/edit/master/_data/people.yaml)
2. Add their profile picture too [`assets/images/bios/`](assets/images/bios/).
3. Use the `compress_bios.sh` or smiliar, to compress their profile picture to an appropriate size.
2. Create a pull request.

_To aid the process, you can send them this:_

> To add you to the website, I will need this information.
> * Your name
> * Are you a PhD student, a master student, or an intern?
> * Your profile picturre in square format. This is optional, if you don't want your face on the website.
> * Your website (this is mandatory)
> * Your co-supervisor, if any.
> * Your start date
> * Your topic of interrests. See https://chandar-lab.github.io/people/ for examples. If you know French, then please provide translations too.

#### If someone leaves the group, then:

1. Remove them from [`_data/people.yaml`](https://github.com/chandar-lab/chandar-lab.github.io/edit/master/_data/people.yaml)
2. Remove their profile picture from [`assets/images/`](assets/images/).
2. Add them to [`_data/alumni.yaml`](_data/alumni.yaml) in the same branch.
3. Create a pull request.

## Local development

As the maintainer you may need to make modification which require local validation:

### Install

```bash
bundle install
```

### Build

```bash
LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8 bundle exec jekyll serve
```
