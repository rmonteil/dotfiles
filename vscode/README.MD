# VSCODE

## Manage Extensions

## Save extensions

```
code --list-extensions > ./extensions.list
```

### Install extentions

```
cat ./extensions.list |% { code --install-extension $_ }
```

