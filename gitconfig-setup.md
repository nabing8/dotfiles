#### .gitconfig

```
[credential]
    helper = store
[user]
    email = Nabin Gyawali
    name = ngyawali8@gmail.com

[includeIf "gitdir:[path here]"]
    path = .gitconfig-[example-config]
[core]
    editor = vim
```

`Note: Include the trailing slash (/) on the path`

#### .gitconfig-[example-config]
```
[user]
    name = nabin.gyawali
    email = nabin.gyawali@nextly.solutions
```

to verify
`git config user.name`
