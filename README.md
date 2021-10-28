# H3EKStringDump
String lists for use with the H3EK dumped using Assembly

Some string lists may be formatted incorrectly, such as having new lines where it should have `|n` or `|r|n`. If you fix up a string list that was broken, feel free to submit it here and I'll correct it so other people can use it.

This isn't a definitive collection of string lists, some will be missing, such as string lists unique to campaign missions. If there's one in particular you'd like uploaded that isn't here, contact me on Discord `Krevil#0933` and I'll grab it for you.

# Additional Notes

When building a cache and playing it on MCC, you may notice your edited strings reverting to their default. This is because as of Season 8 in MCC, some strings are overriden by MCC's files. To get around this, either create a new string in the list or use a new string list - ie, rename `hud_messages` to `hud_messages_new` and it will no longer be overriden.

When saving a new string list .txt file, it must be encoded as UTF16, as seen here in Notepad's save prompt:
![example](https://i.imgur.com/96uWbZj.png)
