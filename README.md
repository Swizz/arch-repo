## Build a package
```sh
aur build -d swizz -cR <package>
```

## Add an existing aur package
```sh
aur sync -d swizz -cR <package>
```

## Update all aur packages
```sh
aur sync -d swizz -u
```

## Commit repo changes
```sh
git commit -m "$(date +'%Y-%m-%d %H:%M:%D')"
```
