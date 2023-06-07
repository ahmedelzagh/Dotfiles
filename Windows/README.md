## My PowerShell & Starship config

- Install starship [docs](https://starship.rs/guide/#%F0%9F%9A%80-installation):
```shell
winget install --id Starship.Starship
```
- Set up PowerShell to use Starship:
*Add the following to the end of your PowerShell configuration (find it by running $PROFILE):*
```shell
Invoke-Expression (&starship init powershell)
```
- Copy `starship.toml` to `%USERPROFILE%\.config`
- Configure Starship more! [Configuration Docs](https://starship.rs/config/)