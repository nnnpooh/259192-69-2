# 259192 - Skills for Professionalism and Entrepreneurship

> Term 2569/2

# Resources

- [Diagram](https://link.excalidraw.com/l/9PltHIQHZMD/97g3a97dWzd)
- [Youtube Playlist](#)

# Demo

- [Form](https://script.google.com/macros/s/AKfycbzAqVp_fHHfoG-_ps0zWaBpFitKqM2_tybKaqqNeFtKsiRZAn8JhCuYCCI2OuyDWy9pzQ/exec)
- [Dashboard](https://datastudio.google.com/s/mmiReemdReE)

# AppSheet

- Current time

```
NOW()
```

- Data Validity

```
[end_time] > [start_time]
```

- Virtual column formula

```
CONCATENATE([room], " - " , [name], " - ", [purpose])
```

The following formula is used to set the default value of a column to 1 hour after the current time.

```
NOW() + "001:00:00"
```

# AppScript

- [Code to send email notification](https://gist.github.com/nnnpooh/09f577c7fd44ea2f633d978e8f0846c7#file-appscript_email-js)
