# anisa-downloader

Requirment:
-------------------

```
    PHP 7
    php-curl php-zip php-xml
```

combine funcionality require `ffmepg` installed.

simple usage:

```
    ./anisa -L "url-to-course" -U "username" -P "password"
```

enable combining video and audio:
```
    ./anisa --url "url-to-course" --username "username" --password "password" --combine
```


run web server:

```
    ./anisa -K -T "./path/to/course"
```
