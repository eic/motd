# Message of the day

The message of the day is shown when running the command `eic-news`, or when logging in (at most once per day).

- To start seeing messages of the day, create the file `$HOME/.eic-news`.
- To disable automatic showing of messages on login, create the file `$HOME/.hushlogin`.
- To disable the message of the day entirely, remove the file `$HOME/.eic-news`.

## Submitting messages

The file `index.html` is pure text which is served at https://eic.github.io/motd/index.html. It is printed in its entirety.

The file `hints.html` is pure text which is served at https://eic.github.io/motd/hints.html. One line from it is printed at random.

Pull requests to this repository can be used to update the messages.

Guidelines for messages:
- Keep the messages to a single line (required for hints).
- Consider that terminal windows may wrap your text.
