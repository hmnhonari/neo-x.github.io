# Chandar-lab Website

Jekyll setup and content for https://chandar-lab.github.io/

## Install

```bash
bundle install
```

## Build

```bash
LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8 bundle exec jekyll serve
```

## Maintenance

Generally, updates only need to be made when there are changes regarding, people, publications, or news.

### People

When someone joins or leaves the group, two set of changes needs to happen.

Their profile description in [`_i18n/en/people.md`](_i18n/en/people.md) and [`_i18n/fr/people.md`](_i18n/fr/people.md) should be updated. The collage in [`_includes/collage.html`](_includes/collage.html) should be updated.

### Publications

When a publication is added or changed, update [`publications.md`](publications.md). Remember to update the `{: reversed="reversed" start="[number]"}` instruction.

### News

When the news section needs to be changed, update [`_i18n/en/index.md`](_i18n/en/index.md) and [`_i18n/fr/index.md`](_i18n/fr/index.md).
