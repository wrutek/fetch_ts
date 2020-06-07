# Fetch ts #

This is a simple bash script for fetching and joining ts movie segments based on `m3u8` index file.

## Installation ##

1. Clone this repository or download `fetch_ts_movies` file.
2. Put `fetch_ts_movies` into one of paths listed int `$PATH` variable

e.g.
```bash
wget https://github.com/wrutek/fetch_ts/blob/master/fetch_ts_movies
cp fetch_ts_movies ~/.local/bin/
```

## Usage ##

```bash
fetch_ts_movies https://remote.host.with.index.file/index.m3u8 my.awesome.movie.mp4
```

If you will not provide second argument (the name of output file) this script will name this file by itself in a format `${date_in_unix_format}.stream.mp4`

## Contribution ##

If you have any issues feel free to create one or just fix it :).

