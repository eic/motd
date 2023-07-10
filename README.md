# Message of the day

The message of the day is shown when running the command `eic-news`, or when logging in (at most once per day).

- To start seeing messages of the day, run the `eic-news` command once.
- To disable automatic showing of messages on login, create the file `$HOME/.hushlogin`.
- To disable the message of the day entirely, remove the file `$HOME/.eic-news`.

## Submitting messages

The file `index.html` is pure text which is served at https://eic.github.io/motd. Pull requests to this repository can be used to update the message.

Guidelines for messages:
- Keep the message to two lines or less.
- Consider that terminal windows may wrap your text.
