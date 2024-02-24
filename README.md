```

## Deployment

Deployment to GitHub pages happens automatically upon pushing the master branch to the upstream repository by means of a GitHub Action.

In order to deploy to GitHub pages manually, commit all changes, then run:

```
./publish_to_ghpages.sh && git push upstream gh-pages
```
