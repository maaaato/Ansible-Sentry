# ansible sentry

## Description

Install sentry in Ubuntu.

## Install

```
sentry init
sentry start http
sentry worker celery worker -B -l WARNING
```

# Author

[Masayuki Nakano](https://github.com/maaaato)
