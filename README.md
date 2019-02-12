# fetch-radio-romania-actualitati-podcasts

Get the latest 10 episodes of every show from Radio România Actualități.

It has two modes:
- one which creates HTML redirects:
```
./fetch-radio-romania-actualitati-podcasts
```
- one which downloads the actual audio file:
```
./fetch-radio-romania-actualitati-podcasts -d|--download
```

If used as service, it repeats every one hour.

Run `./install` to install as a service, it usually requires root access.

Episodes will be found in `/usr/share/radio-romania-actualitati-podcasts/${show}`.

Version 1.0


## Dependencies

Install them yourself:
- [curl](https://curl.haxx.se) - retrieve data from servers
- [gohttpserver](https://github.com/codeskyblue/gohttpserver) - serves the data on the web
- [pup](https://github.com/ericchiang/pup) - HTML parser
- [wget](https://www.gnu.org/software/wget) - retrieve data from web servers


## Support the maintainer

<noscript><a href="https://liberapay.com/andrei/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
