# Repo B to be a subrepo at subrepo-host

This repo is to be in sync with a subdirectory at 
[subrepo-host](https://github.com/OleksiyRudenko/subrepo-host/)
to test git-subrepo workflow

The steps below numbering is consistent across both
[subrepo-host](https://github.com/OleksiyRudenko/subrepo-host)
and [subrepo-repo-b](https://github.com/OleksiyRudenko/subrepo-repo-b)

(3) Add changes and `git commit -m "Add STR"`

(4) Add changes and `git commit -m "Add STR 4"`

(8) Add changes while in `subrepo-host`; commit under `subrepo-host`

(13) On remote (github):
    - create PR
    - merge PR to `master`
    - browse commits under `master`
```
* e138ae0   Merge pull request #1 from OleksiyRudenko/patch01  …
* 0ea1f9f   Add STR 6, 7, 8, 9 to the host repo and subrepoB/
* 0469ab5   Add STR 4
* 105e204   Add STR
* 13a7b2a   Update README.md
* ef38e97   Initial commit
```

(16) Add changes and `git commit -m "Add STR 16 (subrepoB only)"`

(17) Add changes and `git commit -m "Add STR 17 (subrepoB only)"`

(19) On remote (github):
     - create PR
     - merge PR to `master`

(20) Add changes and `git commit -m "Add STR 19, 20 (repoB only)"`

(21) Add changes and `git commit -m "Add STR 21 (repoB only)"`

(22) Add changes and `git commit -m "Add STR 22 (repoB only)"`

(26) Add changes and `git commit -m "Add STR 26 (repoB only)"`

(27) Add changes and `git commit -m "Add STR 27 (repoB only)"`

(28) Add changes and `git commit -m "Add STR 28 (subrepoB only)"`

(29) Add changes and `git commit -m "Add STR 29 (subrepoB only)"`

(33) On remote (github):
    - create PR
    - merge PR to `master`
    - browse commits under `master`
```
* 421f502   Merge pull request #3 from OleksiyRudenko/patch02
* 3726419   Add STR 29 (subrepoB only)
* fb3b8ab   Add STR 28 (subrepoB only)
* 395ce7a   Add STR 27 (repoB only)
* a13cf0b   Add STR 26 (repoB only)
* dfdccbe   Add STR 22 (repoB only)
* 861a87d   Add STR 21 (repoB only) 
* 50a6a94   Add STR 19, 20 (repoB only)
* b612c73   Update README.md
* 517a405   Merge pull request #2 from OleksiyRudenko/patch01
* b59c473   Merge branch 'master' into patch01
* f20cb9e   Add STR 17 (subrepoB only)
* 9e8ac2b   Add STR 16 (subrepoB only)
* 8fab4d5   git subrepo pull subrepoB  … 
* 75842ef   Add STR 13
* e138ae0   Merge pull request #1 from OleksiyRudenko/patch01
* 0ea1f9f   Add STR 6, 7, 8, 9 to the host repo and subrepoB/
* 0469ab5   Add STR 4
* 105e204   Add STR
* 13a7b2a   Update README.md
* ef38e97   Initial commit
```

(34) Add changes and `git commit -m "Add STR 33, 34 (repoB only)"`
