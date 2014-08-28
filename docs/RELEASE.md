## Release Fieldtrip GB

### Android

#### Install Official Release

```
fab clean
fab install_project:project_branch=<x.x.x>
```

Note: project_branch will normally be a tag.  You will prevented from releasing a LIVE version if you use the master branch.

#### Release BETA Version

```
fab release_android
```

#### Release LIVE Version

```
fab release_android:beta=False
```

You will be prompted for a keystore passphrase.
