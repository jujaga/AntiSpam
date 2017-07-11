# AntiSpam
![Version 1.2.1](https://img.shields.io/badge/Version-1.2.1-blue.svg)
![API 2.1](https://img.shields.io/badge/API-2.1-green.svg)
[![Build status](https://ci.appveyor.com/api/projects/status/k15jfavmee442ok1?svg=true)](https://ci.appveyor.com/project/jujaga/antispam)

Introduction
-----
This plugin provides a chat filter, allowing automatic filtering of "spam".

Permissions
-----
`antispam.ignore`<br />
User's chat will not be filtered by this plugin.

Configuration
-----
_antispamconfig.json_

| Option | Type | Default |
|---|---|---|
|DisableBossMessages|Boolean|false|
|DisableOrbMessages|Boolean|false|
|Action|string|"ignore"|
|CapsRatio|double|0.66|
|CapsWeight|double|2.0|
|NormalWeight|double|1.0|
|ShortLength|int|4|
|ShortWeight|double|1.5|
|Threshold|double|5.0|
|Time|int|5|
