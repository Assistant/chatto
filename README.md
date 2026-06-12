### How to use
Download `chatto.html` and use it with an OBS browser source, either by checking the `Local file` option and selecting the file, or by setting its location in the `URL` field prefixed with `file://`. It can also be thrown on a webserver if desires. Using the `URL` method is recommended for local use.

You will need to authenticate with Twitch, navigate to [twitch.tv/activate](https://twitch.tv/activate) and enter the code shown in the OBS browser source.

Style with CSS as desired in the OBS browser source `Custom CSS` option.

### Options
Options are passed as URL paramenters.
You can enable messages disappearing after `n` seconds with `timeout=n` to the URL.
If you're running multiple instances each needs a unique ID passed with `id=x`.
