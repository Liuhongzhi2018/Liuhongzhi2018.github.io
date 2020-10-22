# Liuhongzhi2018.github.io

GitHub Homepages

## Install Ruby
```bash
sudo add-apt-repository ppa:brightbox/ruby-ng
sudo apt-get update

# remove old
sudo apt-get purge --auto-remove ruby

# install new
sudo apt-get install ruby2.6 ruby2.6-dev

ruby -v
```

## Install jekyll
```bash
sudo gem install jekyll

jekyll -v
jekyll new new-site
cd new-site
jekyll serve
```

在浏览器里打开http://localhost:4000可以看到预览效果。


## Reference

Refer to [jekyll CN](https://jekyllcn.com/) and [jekyll EN](https://jekyllrb.com/docs/).

And [jekyll GitHub](https://github.com/jekyll/jekyll).
