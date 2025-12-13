https://docs.asterisk.org/Getting-Started/Hello-World/#start-asterisk

Test with "soft phone"
----------------------

https://www.zoiper.com/ works.
I tested on Android. The first screen is scary looking like it needs some cloud login,
but you just give your `username@<asterisk IP>` and it actually works.

Then dial `100` extension.


Troubleshooting
---------------

When things are ok, on startup you are expected to see as final log line:

```
Asterisk Ready.
```


### Lots of errors in config file

"declined to load" just means the module is not planned to be loaded. It's not actually an error.
