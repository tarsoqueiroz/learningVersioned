# Learning Versioned

## About

Simple steps to versioning a study or experiment and showing your evolution along the time. The basic idea is using simple git commands to do it.

## Version 0.00

Change `primary` branch for `versin-0`.

If you had clone the repo, run this command locally for update:

```sh
git branch -m primary version-0
git fetch origin
git branch -u origin/version-0 version-0
git remote set-head origin -a
```

Access this version by command:

```sh
git checkout version-0
```

Simple tasks to populate `version-0` branch:

```sh
echo "version 0" > version-0.txt
```

And update this version:

```sh
git add .
git commit -m "Final tasks for version 0"
git push
```

Create a new branch:

```sh
git checkout -b version-1
```

