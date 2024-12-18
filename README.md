# README
![github](assets/image.png)
## Q1 Removing Branches Locally and Remotely

### Removing a Local Branch

```bash
git branch -d branch_name
```

### Removing a Remote Branch

``` bash
git push origin :branch_name
```


### Q2 Checkout Another Branch Without Committing Changes

``` bash
git stash
git checkout branch_name
```

### Q3 Listing Tags

``` bash
git tag
```

### Q4 Deleting Tags Locally and Remotely

## Deleting a Local Tag

``` bash
git tag -d tag_name
```

## Deleting a Remote Tag

```bash
git push origin --delete tag_name
```
or
```bash
git push origin :tag_name
```
