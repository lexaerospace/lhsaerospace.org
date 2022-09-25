## Lexington Aerospace Club

Lexington Aerospace Club Website
http://lhsaerospace.org/

## Installation

```
git clone https://github.com/dacarreno/lhsaerospace.org.git
jekyll serve --watch
```

## Deployment

```
jekyll build
rsync -avz --delete _site/ my_website.com:/home/my_user/lhsaerospace.org
```
