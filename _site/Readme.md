Install Jekyll on Ubuntu

1. Install Ruby
```bash
sudo apt-get install ruby-full build-essential zlib1g-dev
```

2. Setup gem installation directory

```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

3. Install Jekyll and Bundler:

```bash
gem install jekyll bundler
```


To start development:

```bash
bundle exec jekyll serve
```


This build is based on mmistakes. Utilize the following for docs:

https://mmistakes.github.io/minimal-mistakes/docs/
