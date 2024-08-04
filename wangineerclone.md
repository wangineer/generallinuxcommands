##Step 1: Do a git Clone

kevin@ct-wangineer-github:~$ ls
gems
kevin@ct-wangineer-github:~$ git clone https://github.com/wangineer/wangineer.github.io.git
Cloning into 'wangineer.github.io'...
remote: Enumerating objects: 213, done.
remote: Counting objects: 100% (213/213), done.
remote: Compressing objects: 100% (151/151), done.
remote: Total 213 (delta 97), reused 121 (delta 44), pack-reused 0
Receiving objects: 100% (213/213), 1.70 MiB | 7.88 MiB/s, done.
Resolving deltas: 100% (97/97), done.
kevin@ct-wangineer-github:~$


##Step 2: Get into the new repo
cd wangineer.github.io




##Step 3: You need to issue Bundle but if you do it initially it seems to provide HTML-proofer error
kevin@ct-wangineer-github:~/wangineer.github.io$ bundle
Fetching gem metadata from https://rubygems.org/...........
Resolving dependencies...
Could not find compatible versions

Because html-proofer >= 5.0.0 depends on Ruby >= 3.1, < 4.0
  and Gemfile depends on html-proofer ~> 5.0,
  Ruby >= 3.1, < 4.0 is required.
So, because current Ruby version is = 3.0.2,
  version solving has failed.
kevin@ct-wangineer-github:~/wangineer.github.io$


##Step 4: Complete the Bundle
kevin@ct-wangineer-github:~/wangineer.github.io$ bundle
Fetching gem metadata from https://rubygems.org/...........
Resolving dependencies...
Bundle complete! 5 Gemfile dependencies, 54 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
1 installed gem you directly depend on is looking for funding.
  Run `bundle fund` for details
kevin@ct-wangineer-github:~/wangineer.github.io$

