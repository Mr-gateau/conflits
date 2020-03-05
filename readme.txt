[master 75311ac] readme modif
 1 file changed, 1 insertion(+), 1 deletion(-)
wilder@wilder-ThinkPad-T430:~/conflits$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/Mr-gateau/conflits
   2ba1051..ba5e42e  master     -> origin/master
Auto-merging readme.txt
CONFLICT (content): Merge conflict in readme.txt
Automatic merge failed; fix conflicts and then commit the result.
wilder@wilder-ThinkPad-T430:~/conflits$ git push
Username for 'https://github.com': Mr-gateau
Password for 'https://Mr-gateau@github.com': 
To https://github.com/Mr-gateau/conflits.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/Mr-gateau/conflits.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
wilder@wilder-ThinkPad-T430:~/conflits$ clear

wilder@wilder-ThinkPad-T430:~/conflits$ git clone https://github.com/Mr-gateau/conflits.git
Cloning into 'conflits'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
wilder@wilder-ThinkPad-T430:~/conflits$ cd conflits
wilder@wilder-ThinkPad-T430:~/conflits/conflits$ git add .
wilder@wilder-ThinkPad-T430:~/conflits/conflits$ git commit "test"
error: pathspec 'test' did not match any file(s) known to git.
wilder@wilder-ThinkPad-T430:~/conflits/conflits$ git commit -m "test"
[master 57ca19e] test
 1 file changed, 1 insertion(+), 1 deletion(-)
wilder@wilder-ThinkPad-T430:~/conflits/conflits$ git push
Username for 'https://github.com': Mr-gateau
Password for 'https://Mr-gateau@github.com': 
To https://github.com/Mr-gateau/conflits.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/Mr-gateau/conflits.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
wilder@wilder-ThinkPad-T430:~/conflits/conflits$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/Mr-gateau/conflits
   ba5e42e..a34688b  master     -> origin/master
Auto-merging readme.txt
CONFLICT (content): Merge conflict in readme.txt
Automatic merge failed; fix conflicts and then commit the result.
wilder@wilder-ThinkPad-T430:~/conflits/conflits$ 
