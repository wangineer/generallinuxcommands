https://jekyllrb.com/docs/installation/ubuntu/


sudo apt-get install ruby-full build-essential zlib1g-dev

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc


gem install jekyll bundler








starting fresh
https://jekyllrb.com/docs/installation/

1. Install Ruby
Ruby: https://www.ruby-lang.org/en/downloads/
 tells me to install rbenv a package manager
   https://github.com/rbenv/rbenv
     Step a: install rbenv the package manager
         - sudo apt install rbenv
         -  y
     Step b: Setup your shell to load rbenv
       - rbenv init
    Steb C : close window and re-open for changes to take effect


2: Check Gem Version 
     - gem -v
        initial install showed 3.3.5


Install Git
sudo apt install git



3. install the theme i guess
https://bootstrapstarter.com/template-mediumish-bootstrap-jekyll/
  a. install
          git clone https://github.com/wowthemesnet/mediumish-theme-jekyll.git
     
gem install bundler
bundle install

at bundle install i ran into issue with ruby version
you can install a version 
    ruby install 2.7.1   <  This will install a version
    
Some more rbenv stuff from the github page
https://github.com/rbenv/rbenv
# list latest stable versions:
rbenv install -l

# list all local versions:
rbenv install -L

# install a Ruby version:
rbenv install 3.1.2

