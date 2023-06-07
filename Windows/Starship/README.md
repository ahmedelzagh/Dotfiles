## My PowerShell & Starship config

- [Install starship](https://starship.rs/guide/#%F0%9F%9A%80-installation):
```shell
winget install --id Starship.Starship
```
- Set up PowerShell to use Starship:<br />
 *Add the following to the end of your PowerShell configuration (find it by running $PROFILE):*
```shell
Invoke-Expression (&starship init powershell)
```
- Copy `starship.toml` to `%USERPROFILE%\.config`
- Use [JetBrainsMono Nerd Font](https://www.nerdfonts.com/font-downloads) font
- Configure Starship more! [Configuration Docs](https://starship.rs/config/)