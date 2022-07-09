# Polybar WakaTime status

![img](/img/screenshot.png)

Display your daily coding time from [WakaTime](https://wakatime.com).


## Dependencies

* `curl`
* `jq`
* obviously a wakatime.com account


## Module

```ini
[module/info-wakatime]
type = custom/script
exec = ~/polybar-scripts/info-wakatime.sh
interval = 60
```
