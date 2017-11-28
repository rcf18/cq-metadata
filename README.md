# cq-metadata
SQLite metadata for Capital Query Project.

[![asciicast](https://asciinema.org/a/S708MosEHFWICWNvRjYyf9ATh.png)](https://asciinema.org/a/S708MosEHFWICWNvRjYyf9ATh)

```shellsession
$ sqlite3 cq.sqlite
SQLite version 3.16.0 2016-11-04 19:09:39
Enter ".help" for usage hints.
sqlite> .tables
attendance      congressmember  hearing         person          speech
committee       constituency    membership      speakers        witness
sqlite> select * from speakers;
5|1
17|2
12|3
sqlite> ^D
$ exit
```
