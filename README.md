# OH-MY-POSH SCHEME

## Instalation

Depending on your system, you can folow the installation from [OH-MY-POSH](https://ohmyposh.dev/docs/)

## Windows Configration

On Windows, you can run add the line bellow to customize using this theme: 
### First open the $PROFILE file:

```shell
notepad $PROFILE
```

### Then add the line bellow:
For Windows Powershell :

```shell
oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/Nickael/ohmyposh.theme/master/.nr.nordic.omp.json' | Invoke-Expression
```

For Bash :

```shell
eval "$(oh-my-posh init bash --config 'https://raw.githubusercontent.com/Nickael/ohmyposh.theme/master/.nr.nordic.omp.json')"
```

For Zsh :

```shell
eval "$(oh-my-posh init zsh --config 'https://raw.githubusercontent.com/Nickael/ohmyposh.theme/master/.nr.nordic.omp.json')"
```
