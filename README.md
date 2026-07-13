# AMPTemplates

Custom AMP (CubeCoders) game templates, forked from the official
[CubeCoders/AMPTemplates](https://github.com/CubeCoders/AMPTemplates).

## The Isle (EVRIMA) [GitGud]

A tweaked version of the The Isle Evrima template. The stock template does not
write the game port into `Game.ini`, so Evrima publishes the default query port
to the server browser instead of the one you set. This version adds
`QueryPort={{GamePort}}` to the generated `Game.ini` (backed by a hidden
`GamePort` setting in the config manifest), so the server advertises the correct
port and shows up properly.

Base template by Greelan. Fork maintained by Mecistios.
