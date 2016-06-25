# euro-cli

> CLI commands to show latest update from UEFA Euro 2016. All data provided by [Football Data API](http://api.football-data.org)


<img src="https://raw.githubusercontent.com/yuripertamax/euro-cli/master/illustration.jpg" width="360">

## Why?

Are you too lazy to type `your-country-name euro 2016` on [google.com](http://google.com)? This simple app will give you information about your favorite team(s) or country(ies) just with CLI command. All data provided by [Football Data API](http://api.football-data.org)

## Features

- Show country stats
- Show current country group with classement table and match results table


## Install

```
$ git clone
$ npm install
```


## Usage

```
$ ./app.js Iceland
```

```js
Iceland Match Results
-----------------------------
(1-1) Portugal vs Iceland
(1-1) Iceland vs Hungary
(2-1) Iceland vs Austria
(null-null) England vs Iceland


[GROUP F] Classement
┌────────────────────┬─────┬─────┬─────┬─────┬──────────┐
│ Country            │ P   │ F   │ A   │ D   │ Point    │
├────────────────────┼─────┼─────┼─────┼─────┼──────────┤
│ Hungary            │ 3   │ 6   │ 4   │ 2   │ 5        │
├────────────────────┼─────┼─────┼─────┼─────┼──────────┤
│ Iceland            │ 3   │ 4   │ 3   │ 1   │ 5        │
├────────────────────┼─────┼─────┼─────┼─────┼──────────┤
│ Portugal           │ 3   │ 4   │ 4   │ 0   │ 3        │
├────────────────────┼─────┼─────┼─────┼─────┼──────────┤
│ Austria            │ 3   │ 1   │ 4   │ -3  │ 1        │
└────────────────────┴─────┴─────┴─────┴─────┴──────────┘
```


## License

MIT