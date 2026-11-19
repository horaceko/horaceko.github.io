---
layout: post
title: Choosing boring technology for a personal site
---

This is a draft used to check the styles. It lives in `_drafts/`, so it is never published. Preview it with `bundle exec jekyll serve --drafts`.

Every few years I rebuild my website, and every time the rebuild takes longer than the writing it was supposed to enable. This time I set one rule: the site has to get out of the way. [Jekyll on GitHub Pages](https://pages.github.com/) fits.

## What "boring" buys you

Boring tools have known failure modes. When something breaks, someone else has already written about it. *Emphasis* and **strong** text look like this.

> The best personal site is the one you actually write on.

- A list item
- Another list item, long enough to wrap onto a second line so the hanging indent can be checked.

1. First
2. Second

Configuration lives in `_config.yml`:

```yaml
title: Horace
url: https://horaceko.github.io
plugins:
  - jekyll-feed
```

```ruby
def greet(name)
  puts "Hello, #{name}" # a comment
end
```

### A smaller heading

The rest of the effort goes into the writing.[^1]

---

[^1]: Footnotes come from kramdown, which GitHub Pages uses by default.
