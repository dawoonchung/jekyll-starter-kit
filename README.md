# Jekyll Starter Kit
This kit simply sets up [Jekyll](https://jekyllrb.com) with [Bootstrap 4](https://getbootstrap.com) with minimal theme.
The purpose of this kit is to educate and enable collaborating with people who are capable of doing simple HTML and CSS.

# How to install
This guide assumes you are using a macOS, as I mostly work with designers (and honestly I haven't tried it on other platforms...)

1. You will need to install [Homebrew](brew.sh) first. Simply copy-paste the following code in terminal and hit enter:
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
Some instructions will be given during the installation and it might ask you to enter system password.

2. When the installation is complete, now copy-paste the following code and run:
```
brew install node
```
This will install [NodeJS](https://nodejs.org), which is needed to use [Bootstrap](https://getbootstrap.com).

3. Finally, we will install [Jekyll](https://jekyllrb.com). macOS ships [Ruby](https://www.ruby-lang.org) by default, so you only need to run:
```
gem install jekyll bundle
```
Now all the basic setups are ready.

4. Go to a directory where you desire to work on, and run:
```
git clone https://github.com/dawoonchung/jekyll-starter-kit
```

5. Afterwards, go to your directory and run:
```
bundle install && npm install
```

6. Finally, run:
```
bundle exec jekyll serve
```
This will run your website!

Now you are ready to experiment with this kit. Good luck!
