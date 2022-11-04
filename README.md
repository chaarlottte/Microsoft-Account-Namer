# Microsoft Account Namer
Sets the username on Microsoft accounts for you. Made by [charlotte](https://github.com/chaarlottte).

May get you temporarily banned from Microsoft if you use the multithreaded option. Bans only last an hour or two, sometimes less. I'd recommend setting `multithread` to `false` in `config.json`.

## How to use
Put all of your accounts in the file `toname.txt`. Set up your config.json like so (minus the comments, of course):

```json
{
    "debug": false, // Whether to enable debug logging. Not needed
    "retry_after_fail": true, // Whether to immediately retry after an error is encountered. Useful if you're running this while AFK.
    "safe_mode": false, // Whether to enable safe mode. This will just make the program slightly slower. If you get IP banned for any amount of time, set this to true.
    "multithread": false // Don't use this unless you want to get IP banned very fast.
}
```

First, go into CMD. `cd` into the directory and run the command `pip install -r requirements.txt`. This will install dependencies.

Then, run the command `python3 main.py`. The command might be different for you depending on your python version (this should work with most modern versions), so if it doesn't work try doing `python`, `python3.10`, or `py` instead of `python3`.

Accounts that are named will be output in `named.txt`.

## But where do I get alts????
[DortGen](https://dortgen.sell.app)

[KingAlts](https://kingalts.shop)

[alts.zone](https://alts.zone)

[alts.top](https://alts.top)

More info on where to get alts and prices can be found here: [AltTracker](https://docs.google.com/spreadsheets/u/4/d/11-mscXuzpf7p9xiwO2uAgSnVlAs9GcGc1MY-u_srdq0/edit)

## License
This code is licensed under [no license](https://choosealicense.com/no-permission/). You can use this code, modify it, whatever, but you cannot sell it or pass it off as your own.
