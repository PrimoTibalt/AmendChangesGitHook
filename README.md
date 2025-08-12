<h2>Setup:</h2>
Just copy `post-commit' into `.git/hooks` of your repository.
<h2>Usage:</h2>

```sh
git commit -m "f"
```

<h2>How it works:</h2>

1. Stash everything that was not commited. The stash won't be created if there are no changes that you did not commit.
2. Reset created commit.
3. Amend changes into previous commit.
4. Pop stash if the first step had created one.
