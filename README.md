# git-shrink

Sometimes space is a premium, and shrinking the space used by .git is useful.

```
$ git clone https://github.com/toddfries/git-shrink.git
$ cd git-shrink
Cloning into 'git-shrink'...
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 15 (delta 2), reused 15 (delta 2), pack-reused 0 (from 0)
Receiving objects: 100% (15/15), done.
Resolving deltas: 100% (2/2), done.
$ cd git-shrink
git-shrink$ ./git-shrink
start:     102 gc:     108 diff:      -6 (0s)
git-shrink$
```

And yes, some small repositories add a few bytes instead of shrinking.

If you move git-shrink into your `$PATH` you can call it via `git shrink`.

