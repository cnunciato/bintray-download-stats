# Bintray stats

```
npm install
```

```
./bin/bintray --help
Usage: bintray [options]

  Options:

    -V, --version              output the version number
    -s, --subject <subject>    Bintray subject (e.g., habitat)
    -r, --repo <repo>          Bintray repo (e.g., stable)
    -p, --package <package>    Bintray package (e.g., hab-x86_64-linux)
    -u, --username <username>  Bintray username
    -k, --key <key>            Bintray API key
    -S, --start <start>        Start date (e.g., 2018-01-01)
    -E, --end <end>            End date (e.g., 2018-12-31)
    -h, --help                 output usage information
```

```
export BINTRAY_USERNAME=<YOUR_USERNAME>
export BINTRAY_KEY=<YOUR_API_KEY>
./bin/bintray
```

By default, it'll return a CSV with download stats by date since January 1 of this year.
