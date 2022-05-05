# fish language module for BBEdit

A BBEdit [codeless language module][clm] for fish, the friendly interactive shell.

[clm]: https://www.barebones.com/support/develop/clm.html

BBEdit's built-in "Unix shell script" language module doesn't fold or index fish functions, or highlight some [fish commands][fcmd]. This language module does.

[fcmd]: https://fishshell.com/docs/current/commands.html

On the other hand it has its own limitations because it is codeless: it doesn't colour variables, it relies on dumb and fragile indentation-matching to match the beginning and end of functions, and it currently behaves undesirably if you use things that look like a fish command but aren't, such as 'time' in `set time`.

A proper codeful language module with intelligent parsing would be a much better alternative. If this tempts you to write one, please do.

Thanks to BBEdit’s deservedly famous and amazing [technical support][ninjas] for helping me iron out some issues.

[ninjas]: https://www.barebones.com/support/

LICENSE: MIT, but honestly, do whatever.