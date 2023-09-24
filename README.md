### Initialize jekyll content
```
$ cd /var/work/listman
$ docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll sh -c "chown -R jekyll /usr/gem && jekyll new blog"
```
