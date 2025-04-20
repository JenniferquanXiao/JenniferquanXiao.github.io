## Quan Xiao's Website

### Thanks
This website is based on a template by Martin Saveski and Mor Naaman using Jekyll. Improvement ideas were taken from the al-folio theme.

### Updates guide
Change one of the files in `_data`, unless you are changing the look of the website.

Test changes with:
```
jekyll serve
```

If there is jekyll serve running, do the following
```
lsof -i :4000
kill -9 <PID>

jekyll serve
```

Push to github
```
git add .
git commit -m "Description of changes (optional)"
git push
```


If not working (probabily due to first time or large change), try
```
git config http.postBuffer 524288000
```
before
```
git push
```


## External Libraries
- Framework: [Jekyll](http://jekyllrb.com/)
- CSS
  - [Skeleton](getskeleton.com)
  - Tabs: [Skeleton Tabs](https://github.com/nathancahill/skeleton-tabs)
  - Experience: [Timeline](https://codepen.io/NilsWe/pen/FemfK)
  - Icons: [Font Awesome](http://fontawesome.io/)
- JS
  - [Jquery (3.1.1)](https://jquery.com/)