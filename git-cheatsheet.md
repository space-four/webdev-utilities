## Managing your Remote Repository

### List your existing Remote Repositories

```
$ git remote -v
```

Will list your existing Remote Repositories.

Output should look like this:

```
origin git@your.git.repo.example.com:user/repository.git (fetch)
origin git@your.git.repo.example.com:user/repository.git (push)
```


### Change your Remote Repo

```
$ git remote set-url origin git@your.git.repo.example.com:user/repository2.git
```

Will change your Remote Repository to desired URL.
User `git remote -v` afterwards to make sure.