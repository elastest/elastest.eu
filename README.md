# Introduction
The [elastest.eu](elastest.eu) web is generated with [Jekyll](https://jekyllrb.com/).

You can clone this repository and edit any page with a simple text editor.
```
git clone git@github.com:elastest/elastest.eu.git
```
If you want to preview the changes in local before commiting, you can execute the following command in the root folder of the repository (you need [Docker](https://www.docker.com/) installed) and open the browser in `http://localhost:4000`:
```
docker run --rm --label=jekyll --volume="$(pwd)":/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll bundle exec jekyll serve
```
To update the web page, commit and push your changes. Then, GitHub will update the web [elastest.eu](http://elastest.eu) automatically.
