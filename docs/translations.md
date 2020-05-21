# Translations

Thanks for your interest in helping translating the guides!

## Starting a translation

Before you start working on a translation, look through the [open pull requests](https://github.com/codeforcroatia/assets/pulls) to see if anyone else is already working on one for your language.

If there's not, then today is your day to lead this effort! Here's how to start:

1. [Fork this repository](https://github.com/codeforcroatia/assets/fork)
1. [Set up your environment](hhttps://github.com/github/personal-website#install-in-your-local-development-environment)
1. Create a new branch for your translation work e.g. `hr`.
1. Copy `_data/locales/en.yml` to your target language file e.g. `_data/locales/hr.yml` and translate all the strings.
1. Create a new directory in `_articles/` for your language e.g. `_articles/hr/`, copy each guide from `_articles/` into that folder and translate the content in each guide, except for the field names in the front matter between the `---`s at the top of each file, e.g., `title:` should remain unchanged. Remove the `toc:` fields (they are only used for English).
1. Copy `index.html` to your target language index file e.g. `[_articles/hr/index.html](https://github.com/codeforcroatia/assets/blob/master/_articles/hr/index.html)` and update the `lang:` and add the `permalink:` fields. Example: `lang: hr` and `permalink: /hr/`. All other fields' values must remain unchanged.
1. Run `script/test` and make sure there are no failures with your translation files. Note that you may need to fix broken links.
1. Send a pull request. (You may send a pull request before all steps above are complete: e.g., you may want to ask for help with translations, or getting tests to pass. However your pull request will not be merged until all steps above are complete.)

Completing an initial translation of the whole site is a fairly large task. One way to break that task up is to work with other translators through pull requests on your fork. You can also [add collaborators to your fork](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/inviting-collaborators-to-a-personal-repository) if you'd like to inivte other translators to commit directly to your fork and share responsibility for merging pull requests.

## Updating a translation

### Corrections

If you notice spelling or grammar errors, typos, or opportunities for better phrasing, open a pull request with your suggested fix. If you see a problem that you aren't sure of or don't have time to fix, open an issue.
