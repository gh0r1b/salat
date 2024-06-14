# salat 

## About
a cli tool for muslims who don't wanna leave their terminal .

* check prayers times

```bash
salat
```

* check prayer times in any given date (this year tho)
```bash
salat 20 10
```

* how much until the next prayer ?

```bash
salat -n
```

* search for hadith (usin dorar API) in your terminal (arabic only)

```bash
salat -s "الصلاة"
```

* what is the hijri date?

```bash
salat -d
```

> what else ?

```bash
salat -h # help is work in progress
```

## set up

```bash
git clone https://github.com/gh0r1b/salat.git
mv salat/salat ~/.local/bin/salat
chmod u+x ~/.local/bin/salat
salat -S  # set up your country, city and prefered method
```

## helping out

wanna help ?

report issues, make pull requests, suggest features (or even ideas for a whole other project) and check ##TODO

## TODO

* [ ] better help
