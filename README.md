# No-BS Spinner

No-datastore completely client-side spinner. Configure options as queryparams!

The index.html is hosted through github pages, but you can just re-host it anywhere.

No telemetry, no connectivity required once index.html is loaded.

## Examples

- https://blog.mtib.dev/no-bs-spinner?Cats&Dogs&Snakes&Hamsters&Hedgehogs
- https://blog.mtib.dev/no-bs-spinner/?0&1&2&3&4&5&6&7&8&9
- https://blog.mtib.dev/no-bs-spinner/?🔥&👱‍♀️&👀&🤷‍♂️
- https://blog.mtib.dev/no-bs-spinner (forwards to another example)


## See also

- [no-bs-countdown](https://blog.mtib.dev/no-bs-countdown/#/No%20Bullshit%20Countdown/2024/2/3/23/45) ([github](https://github.com/mtib/no-bs-countdown))
- [paste](https://topaz.github.io/paste/) ([github](https://github.com/topaz/paste))

## Background

I am so annoyed how there are no good simple options for these kinds of applications. I just need one that works, doesn't have ads and can be fed options through the link itself or some API. Future no-bs ideas:

- time diff
- unix time

## Improvement ideas

- option to remove selected item after they have been selected (just spin again)
    - press r to remove
    - spin with r to remove the one before
- colorthemes
    - magic option: `?theme=<supported_theme>`
    - queryparam value: `?Dog={color=red}&Cat={color=#f0f}`
