# multi-angular

## what?
An attempt to run 2 seperate angular versions in 1 browser,
using Polymer modules in an attempt to encapsulate the angular javascript from both apps.

Unfortunally, the javascript does not get encapsulated:
the angular variable is still a global variable, resulting in only 1 version able to run.

## how to run
- install polyserve & bower globally
```
  npm install -g polyserve
  npm install -g bower
```
- install bower packages in root
```
  bower install
```
- run polyserve server in root
```
  polyserve
```
