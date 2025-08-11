```sh
- git commit -m "f"
```
Would trigger the script. It will:
1. Stash everything that was not commited. The stash won't be created if there are no changes that you did not commit.
2. Reset created commit.
3. Amend changes into previous commit.
4. Pop stash if the first step had created one.
