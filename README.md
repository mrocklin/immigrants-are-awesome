Immigrants are Awesome
======================

Small static site listing notable American Immigrants.

This was originally an afternoon project caused by the ban on immigrants from
predominantly Muslim countries starting on 2017-01-27 and the broader
xenophobic political messaging of this period.


How to Contribute
-----------------

Pull requests are welcome.  So far no mechanism exists for the submission of
new content from people unfamiliar with Github.

Copy markdown files in `content/`, and add images in `content/images`.  Here is
an example file:

```
Title: Albert Einstein
Date: 2010-12-03 10:20
How: Overstayed his visa from Germany.
Image: albert.einstein.jpg
Who: One of the greatest physicists of the 20th century.  Figured out crazy
amazing things about light, time, and space. Rocked a stylish mustache.
Link: https://en.wikipedia.org/wiki/Albert_Einstein
```

Disclaimer on Content
---------------------

Content was sourced from a variety of people.  The maintainer of this
repository has not thoroughly vetted this content.  Please report factual
errors.


Build Locally
-------------

    git clone https://github.com/mrocklin/immigrants-are-awesome
    cd immigrants-are-awesome
    make html
    make serve  # hosts at http://localhost:8000

Need pelican-plugins for random page generation and ghp-import for publishing.
There are some hard-coded paths in pelicanconf.py that will need to be tweaked
to your environment.
