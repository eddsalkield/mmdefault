# Setting up the site

## Install [jekyll](https://jekyllrb.com/)

On Fedora:

```
sudo dnf install ruby-devel
gem install jekyll bundler
```

## Set up the repo

Clone the repo:

```
git clone https://github.com/eddsalkield/mmdefault.git
cd mmdefault
```

Install the packages:

```
bundle
```

Build the site and run on the dev server:

```
bundle exec jekyll serve
```

Browse to http://localhost:4000
