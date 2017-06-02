# slapper

__Another load testing tool__

![slapper](https://raw.githubusercontent.com/ikruglov/slapper/master/img/example.gif)

## Usage
```bash
$ ./slapper -help
Usage of ./slapper:
  -maxY duration
        max on Y axe (default 100ms)
  -minY duration
        min on Y axe (default 1ms)
  -rate int
        Requests per second (default 50)
  -targets string
        Targets file (default "stdin")
  -timeout duration
        Requests timeout (default 30s)
  -workers int
        Number of workers (default 8)
```

## Targets syntax
```
GET http://127.0.0.1/_test
$ {"test":"payload"}

```

## Acknowledgement
* Idea and initial implementation is by @sparky
* This module was originally developed for Booking.com.
