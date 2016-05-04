SEO Report
==========

[![Coverage Status](https://coveralls.io/repos/github/drawbuildplay/seo_report/badge.svg?branch=master)](https://coveralls.io/github/drawbuildplay/seo_report?branch=master)
[![Build Status](https://travis-ci.org/drawbuildplay/seo_report.svg?branch=master)](https://travis-ci.org/drawbuildplay/seo_report)

Scan your website for On Page SEO Optimization issues based on 
the SEO guidelines from Google's SEO Starter Guide:
        
http://static.googleusercontent.com/media/www.google.com/en//webmasters/docs/search-engine-optimization-starter-guide.pdf


Usage
-----

```
pip install -e .
seoreport http://www.domain.com /sitemap.xml
```

Testing
-------
```
pip install -r tests/test-requirements.txt
nosetests
```