# mywebsite

> :warning:
  This theme requires ruby and rubygems installed

### Features

* Clean layout
* Resposive layout
* Pagination
* Syntax highlighting
* Social links
* Tags listing page
* Categories listing page
* Google Analytics integration
* Disqus integration

---

### Install and Test

1. Download or clone repo `git clone git@github.com:fladjdd55/mywebsite.git`
2. Enter the folder: `cd mywebsite/`
3. If you don't have bundler installed: `gem install bundler`
3. Install Ruby gems: `bundle install`
4. Start Jekyll server: `bundle exec jekyll serve --watch`

Access via: [http://localhost:4000/mtwebsite/](http://localhost:4000/mywebsite/)

If you would like to run without using the `github-pages` gem, update your Gemfile to the following:

```
source 'https://rubygems.org'
gem 'jekyll-paginate'
gem 'jekyll-watch'
gem 'kramdown'
gem 'kramdown-parser-gfm'
```
---


---

### Copyright and license

It is under [the MIT license](/LICENSE).
