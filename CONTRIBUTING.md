Bfy App
=======

We really appreciate and value contributions to the Bfy.Finance repositories. Please take 5' to review the items listed below to make sure that your contributions are merged as soon as possible.

## Creating Pull Requests (PRs)

As a contributor, you are expected to fork this repository, work on your own fork and then submit pull requests. The pull requests will be reviewed and eventually merged into the main repo. See ["Fork-a-Repo"](https://help.github.com/articles/fork-a-repo/) for how this works.

## A typical workflow

1) Make sure your fork is up to date with the main repository:

```
cd Bfy-app
git remote add upstream https://github.com/atalanta110/bfy-app
git fetch upstream
git pull --rebase upstream master
```
NOTE: The directory `Bfy-app` represents your fork's local copy.

2) Branch out from `master` into `fix/some-bug-#123`:
(Postfixing #123 will associate your PR with the issue #123 and make everyone's life easier =D)
```
git checkout -b fix/some-bug-#123
```

3) Make your changes, add your files, commit, and push to your fork.

```
git add SomeFile.js
git commit "Fix some bug #123"
git push origin fix/some-bug-#123
```

4) Go to [atalanta110/bfy-app](https://github.com/atalanta110/bfy-app) in your web browser and issue a new pull request.

5) Maintainers will review your code and possibly ask for changes before your code is pulled in to the main repository. We'll check that all tests pass, review the coding style, and check for general code correctness. If everything is OK, we'll merge your pull request and your code will be part of Bfy's App.

*IMPORTANT* Please pay attention to the maintainer's feedback, since its a necessary step to keep up with the standards Bfy.Finance attains to.

Thanks for your time and code!
