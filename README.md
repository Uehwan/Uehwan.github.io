# ACSL Webpage

## Development Environment (Mac)
!!For M1 users, refer to [this blog](https://unluckyjung.github.io/develop-setting/2021/01/20/Mac-Jekyll-Setting/)
### Install Ruby
macOS Big Sur 11.x ships with Ruby 2.6.3. Check your Ruby version using ruby -v.

If your mac is not equipped with Ruby, then follow the below steps.
First, you need to install Xcode.
```bash
xcode-select --install
```

Next, install Homebrew to install Ruby
```bash
# installing Homebrew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install ruby

# add Ruby to the system path
echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.bash_profile

# check the installation of ruby
which ruby
# /usr/local/opt/ruby/bin/ruby

ruby -v
# ruby 2.6.3p62 (2019-04-16 revision 67580)
```

### Install Jekyll
Simply run the following
```bash
gem install --user-install bundler jekyll
```

Then, append your path file with the following, replacing the X.X with the first two digits of your Ruby version (ruby -v):
```bash
# If you're using Zsh
echo 'export PATH="$HOME/.gem/ruby/X.X.0/bin:$PATH"' >> ~/.zshrc

# If you're using Bash
echo 'export PATH="$HOME/.gem/ruby/X.X.0/bin:$PATH"' >> ~/.bash_profile

# Unsure which shell you are using? Type
echo $SHELL
```

## Running a Server
You can run a local server as follows:
```bash
bundle exec jekyll serve
```

If it is your first time running a server, execute the below before running a server.
```bash
bundle install
```
