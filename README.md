# My special flavor of jekyll

## Using it

```
docker run --rm --volume="$PWD:/srv/jekyll"  -p 4000:4000 -it jtemporal/personalizedjekyll jekyll serve --livereload
```

## Development

to build:

```
docker build -t personalizedjekyll .
```