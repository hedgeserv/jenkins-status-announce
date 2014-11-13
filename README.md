# Jenkins Status Microbot

## Synopsis

    $ bin/daemon

Before launching the daemon for the first time you must update the three
environment variables at the top of the file: AUTH_TOKEN, ROOM_ID and
BASEURL.

Press control-C to kill the daemon. If you want a long-lived daemon
then run your terminal session inside of GNU screen or `tmux`.

Find me on Twitter `@noahsussman` if you get stuck!

## Notes

This pattern will work with any CI server that has a JSON API
(so&hellip; any CI server). However the jq query and the REST API
query would need to be altered. I suggest forking this project if you
decide to adopt another CI system rather than trying to remain parity
between your use case and Jenkins. I got Jenkins handled, you go
handle your pet CI robot on your own :P



               __           __   _
              / /__  ____  / /__(_)___  _____
         __  / / _ \/ __ \/ //_/ / __ \/ ___/
        / /_/ /  __/ / / / ,< / / / / (__  )
        \____/\___/_/ /_/_/|_/_/_/ /_/____/

                  __        __
            _____/ /_____ _/ /___  _______
           / ___/ __/ __ `/ __/ / / / ___/
          (__  ) /_/ /_/ / /_/ /_/ (__  )
         /____/\__/\__,_/\__/\__,_/____/

                  _                 __          __
       ____ ___  (_)_____________  / /_  ____  / /_
      / __ `__ \/ / ___/ ___/ __ \/ __ \/ __ \/ __/
     / / / / / / / /__/ /  / /_/ / /_/ / /_/ / /_
    /_/ /_/ /_/_/\___/_/   \____/_.___/\____/\__/
