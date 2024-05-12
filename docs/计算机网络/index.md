# 计算机网络
## daolun
### h3
## h2
INFO    -  [21:54:26] Reloading browsers
INFO    -  [21:54:35] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:54:35] Reloading browsers
INFO    -  [21:54:39] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:54:39] Reloading browsers
INFO    -  [21:54:42] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:54:42] Reloading browsers
INFO    -  [21:54:44] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:54:44] Reloading browsers
INFO    -  [21:54:46] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:54:46] Reloading browsers
INFO    -  [21:57:14] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:57:14] Reloading browsers
INFO    -  [21:57:19] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:57:20] Reloading browsers
INFO    -  [21:57:20] Browser connected: http://127.0.0.1:8000/
INFO    -  [21:57:21] Browser connected: http://127.0.0.1:8000/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C/
INFO    -  [21:57:55] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:57:55] Reloading browsers
INFO    -  [21:57:55] Browser connected: http://127.0.0.1:8000/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C/
INFO    -  [21:57:57] Browser connected: http://127.0.0.1:8000/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/
INFO    -  [21:58:00] Browser connected: http://127.0.0.1:8000/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C/
INFO    -  [21:58:00] Browser connected: http://127.0.0.1:8000/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/
INFO    -  [21:58:01] Browser connected: http://127.0.0.1:8000/
INFO    -  [21:58:02] Browser connected: http://127.0.0.1:8000/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C/
INFO    -  [21:58:11] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:58:12] Reloading browsers
INFO    -  [21:58:12] Browser connected: http://127.0.0.1:8000/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C/
INFO    -  [21:58:16] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:58:17] Reloading browsers
INFO    -  [21:58:17] Browser connected: http://127.0.0.1:8000/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C/
INFO    -  [21:58:19] Detected file changes
INFO    -  Building documentation...
INFO    -  [21:58:19] Reloading browsers
INFO    -  [21:58:19] Browser connected: http://127.0.0.1:8000/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C/
INFO    -  [21:58:51] Browser connected: http://127.0.0.1:8000/
^CINFO    -  Shutting down...
❯ mkdocs gh-deploy --force
INFO    -  Cleaning site directory
INFO    -  Building documentation to directory: /home/tgs/blog/csdiy.impl/site
INFO    -  Documentation built in 0.22 seconds
ERROR   -  Cannot deploy - this directory does not appear to be a git repository
WARNING -  Version check skipped: No version specified in previous deployment.
INFO    -  Copying '/home/tgs/blog/csdiy.impl/site' to 'gh-pages' branch and pushing to GitHub.
ERROR   -  Failed to deploy to GitHub with error:
           not a git repository (or any of the parent directories): .git

Deployment Aborted!
❯ git init .
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /home/tgs/blog/csdiy.impl/.git/
❯ mkdocs gh-deploy --force
INFO    -  Cleaning site directory
INFO    -  Building documentation to directory: /home/tgs/blog/csdiy.impl/site
INFO    -  Documentation built in 0.22 seconds
WARNING -  Version check skipped: No version specified in previous deployment.
INFO    -  Copying '/home/tgs/blog/csdiy.impl/site' to 'gh-pages' branch and pushing to GitHub.
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
Traceback (most recent call last):
  File "/home/tgs/.env/csdiy.impl/bin/mkdocs", line 8, in <module>
    sys.exit(cli())
             ^^^^^
  File "/home/tgs/.env/csdiy.impl/lib/python3.12/site-packages/click/core.py", line 1157, in __call__
    return self.main(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/tgs/.env/csdiy.impl/lib/python3.12/site-packages/click/core.py", line 1078, in main
    rv = self.invoke(ctx)
         ^^^^^^^^^^^^^^^^
  File "/home/tgs/.env/csdiy.impl/lib/python3.12/site-packages/click/core.py", line 1688, in invoke
    return _process_result(sub_ctx.command.invoke(sub_ctx))
                           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/tgs/.env/csdiy.impl/lib/python3.12/site-packages/click/core.py", line 1434, in invoke
    return ctx.invoke(self.callback, **ctx.params)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/tgs/.env/csdiy.impl/lib/python3.12/site-packages/click/core.py", line 783, in invoke
    return __callback(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/tgs/.env/csdiy.impl/lib/python3.12/site-packages/mkdocs/__main__.py", line 314, in gh_deploy_command
    gh_deploy.gh_deploy(
  File "/home/tgs/.env/csdiy.impl/lib/python3.12/site-packages/mkdocs/commands/gh_deploy.py", line 129, in gh_deploy
    ghp_import.ghp_import(
  File "/home/tgs/.env/csdiy.impl/lib/python3.12/site-packages/ghp_import.py", line 283, in ghp_import
    git.check_call('push', opts['remote'], opts['branch'], '--force')
  File "/home/tgs/.env/csdiy.impl/lib/python3.12/site-packages/ghp_import.py", line 119, in check_call
    sp.check_call(['git'] + list(args), **kwargs)
  File "/usr/lib/python3.12/subprocess.py", line 413, in check_call
    raise CalledProcessError(retcode, cmd)
subprocess.CalledProcessError: Command '['git', 'push', 'origin', 'gh-pages', '--force']' returned non-zero exit status 128.
❯ git remote add origin git@github.com:tanggengsheng/tanggengsheng.github.io.git
❯ git branch -M master
❯ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:tanggengsheng/tanggengsheng.github.io.git'
❯ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:tanggengsheng/tanggengsheng.github.io.git'
❯ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'github.com:tanggengsheng/tanggengsheng.github.io.git'
❯ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:tanggengsheng/tanggengsheng.github.io.git'
❯ git remote -v
origin  git@github.com:tanggengsheng/tanggengsheng.github.io.git (fetch)
origin  git@github.com:tanggengsheng/tanggengsheng.github.io.git (push)
❯ git push  origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:tanggengsheng/tanggengsheng.github.io.git'
❯ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:tanggengsheng/tanggengsheng.github.io.git'
❯ gst
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        docs/
        mkdocs.yml
        site/

nothing added to commit but untracked files present (use "git add" to track)
❯ git add .
❯ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:tanggengsheng/tanggengsheng.github.io.git'
❯ git commit -m "test"
[master (root-commit) e7c506b] test
 54 files changed, 9419 insertions(+)
 create mode 100644 docs/index.md
 create mode 100644 "docs/\346\223\215\344\275\234\347\263\273\347\273\237/index.md"
 create mode 100644 "docs/\350\256\241\347\256\227\346\234\272\347\275\221\347\273\234/index.md"
 create mode 100644 mkdocs.yml
 create mode 100644 site/404.html
 create mode 100644 site/assets/images/favicon.png
 create mode 100644 site/assets/javascripts/bundle.a7c05c9e.min.js
 create mode 100644 site/assets/javascripts/bundle.a7c05c9e.min.js.map
 create mode 100644 site/assets/javascripts/lunr/min/lunr.ar.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.da.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.de.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.du.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.el.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.es.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.fi.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.fr.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.he.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.hi.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.hu.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.hy.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.it.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.ja.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.jp.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.kn.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.ko.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.multi.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.nl.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.no.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.pt.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.ro.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.ru.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.sa.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.stemmer.support.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.sv.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.ta.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.te.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.th.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.tr.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.vi.min.js
 create mode 100644 site/assets/javascripts/lunr/min/lunr.zh.min.js
 create mode 100644 site/assets/javascripts/lunr/tinyseg.js
 create mode 100644 site/assets/javascripts/lunr/wordcut.js
 create mode 100644 site/assets/javascripts/workers/search.b8dbb3d2.min.js
 create mode 100644 site/assets/javascripts/workers/search.b8dbb3d2.min.js.map
 create mode 100644 site/assets/stylesheets/main.66ac8b77.min.css
 create mode 100644 site/assets/stylesheets/main.66ac8b77.min.css.map
 create mode 100644 site/assets/stylesheets/palette.06af60db.min.css
 create mode 100644 site/assets/stylesheets/palette.06af60db.min.css.map
 create mode 100644 site/index.html
 create mode 100644 site/search/search_index.json
 create mode 100644 site/sitemap.xml
 create mode 100644 site/sitemap.xml.gz
 create mode 100644 "site/\346\223\215\344\275\234\347\263\273\347\273\237/index.html"
 create mode 100644 "site/\350\256\241\347\256\227\346\234\272\347\275\221\347\273\234/index.html"
❯ git push -u origin master
Enumerating objects: 70, done.
Counting objects: 100% (70/70), done.
Delta compression using up to 6 threads
Compressing objects: 100% (61/61), done.
Writing objects: 100% (70/70), 575.09 KiB | 1.43 MiB/s, done.
Total 70 (delta 6), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (6/6), done.
To github.com:tanggengsheng/tanggengsheng.github.io.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
❯ mkdocs gh-deploy --force
INFO    -  Cleaning site directory
INFO    -  Building documentation to directory: /home/tgs/blog/csdiy.impl/site
INFO    -  Documentation built in 0.22 seconds
INFO    -  Copying '/home/tgs/blog/csdiy.impl/site' to 'gh-pages' branch and pushing to GitHub.
Enumerating objects: 64, done.
Counting objects: 100% (64/64), done.
Delta compression using up to 6 threads
Compressing objects: 100% (58/58), done.
Writing objects: 100% (64/64), 574.41 KiB | 1.37 MiB/s, done.
Total 64 (delta 7), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (7/7), done.
remote:
remote: Create a pull request for 'gh-pages' on GitHub by visiting:
remote:      https://github.com/tanggengsheng/tanggengsheng.github.io/pull/new/gh-pages
remote:
To github.com:tanggengsheng/tanggengsheng.github.io.git
 * [new branch]      gh-pages -> gh-pages
INFO    -  Your documentation should shortly be available at: https://tanggengsheng.github.io/tanggengsheng.github.io/
❯ gst
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
❯ gst
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
❯ mkdocs gh-deploy --force
INFO    -  Cleaning site directory
INFO    -  Building documentation to directory: /home/tgs/blog/csdiy.impl/site
INFO    -  Documentation built in 0.23 seconds
INFO    -  Copying '/home/tgs/blog/csdiy.impl/site' to 'gh-pages' branch and pushing to GitHub.
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 213 bytes | 213.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:tanggengsheng/tanggengsheng.github.io.git
   e2e3f25..a3248dc  gh-pages -> gh-pages
INFO    -  Your documentation should shortly be available at: https://tanggengsheng.github.io/tanggengsheng.github.io/
❯ ls
docs  mkdocs.yml  site
❯ mkdocs gh-deploy --force
INFO    -  Cleaning site directory
INFO    -  Building documentation to directory: /home/tgs/blog/csdiy.impl/site
INFO    -  Documentation built in 0.22 seconds
INFO    -  Copying '/home/tgs/blog/csdiy.impl/site' to 'gh-pages' branch and pushing to GitHub.
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 213 bytes | 213.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:tanggengsheng/tanggengsheng.github.io.git
   a3248dc..19e56f4  gh-pages -> gh-pages
INFO    -  Your documentation should shortly be available at: https://tanggengsheng.github.io/tanggengsheng.github.io/

❯ ls
docs  mkdocs.yml  site
❯ ls -a
.  ..  .git  docs  mkdocs.yml  site
❯ mkdir .github
❯ cd .github
❯ mkdir workflow
❯ cd workflow
❯ vi ci.yml
❯ cd ../../
❯ git add *
'%                                                                                                                      ❯ git commit -m "test"
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .github/

nothing added to commit but untracked files present (use "git add" to track)
❯ gst
On branch master
```c++
#include <iostream>
using namespace std;

int main()
{
    std::cout << "Hello World" << std::endl;
    return 0;
}
```
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .github/

nothing added to commit but untracked files present (use "git add" to track)
❯ git add .
❯ gst
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .github/workflow/ci.yml

❯ git commit -m "test"
[master 4406d78] test
 1 file changed, 29 insertions(+)
 create mode 100644 .github/workflow/ci.yml
❯ git push  origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 6 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 792 bytes | 264.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:tanggengsheng/tanggengsheng.github.io.git
   e7c506b..4406d78  master -> master

~/blog/csdiy.impl master                                                                            csdiy.impl 22:36:34
❯