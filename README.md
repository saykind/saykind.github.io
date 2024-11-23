My personal website is using a [Github Pages template for academic websites](https://academicpages.github.io), which was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.


### Instructions 

To run it locally on MacOs install ruby (and add it to `$PATH`) then install node.js
```bash
brew install ruby
brew install node
```

Using Ruby, install bundler and jekyll (add gem `EXECUTABLE DIRECTORY` to `$PATH`)
```bash
gem install bundler
gem install jekyll
```

Start local server
```bash
bundle install
bundle exec jekyll serve
```

In browser of your choice, visit http://localhost:4000 or whatever `Server address` last command outputs.