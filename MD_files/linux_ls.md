Determine Which File Is the Oldest

To list the directory and sort by date,
 we use -l for "long listing",
  -A for "almost all", and -t for "sort by time".

```ls -lAt ~/Practice/Test/var/log/ ```

Determine Which File Is the Largest

To list the directory and sort by file size, we use -l ("long listing") and -S ("sort by file size").

```ls -lS ~/Practice/Test/var/log/```

Determine When the File `~/Practice/Test/sos_commands/networking/netstat_-W_-neopa` was Last Modified

We use a simple -l for "long listing" to view the last modified time and date.

```ls -l ~/Practice/Test/sos_commands/networking/netstat_-W_-neopa```

Determine When the File `~/Practice/Test/sos_commands/networking/netstat_-W_-neopa` Was Last Accessed

To view access times, we use -l ("long listing") and-u` (access time).

```
ls -lu ~/Practice/Test/sos_commands/networking/netstat_-W_-neopa
```