# twsr

Spaced Repetition system for TiddlyWiki. Doesn't require any external managers like Anki.

Check the demo and import the plugin here: https://tadeas.dev/twsr

## Features

- Create flashcards from tiddlers just by adding a tag
- Revise your flashcards through the sidebar
- Cloze prompts and custom prompts supported (otherwise uses tiddler title as prompt by default)
- "Collection tiddlers": all of your german word flashcards in one tiddler for example
- Control over parameters that determine spacing intervals
  - Anki's algorithm is used
  - You don't need to touch anything for things to work, but you can tweak things if you want
- Control over delays (so you can add flashcards and initialize them with a 10 day delay for example)

## TODO

- after `again`, ensure the card doesn't repeat until you've seen all current ones
- import functionality and in general making the migration from TiddlyWiki + Anki (or equivalent) to just TiddlyWiki smoother
- way to see your performance, for example with the d3 plugin and a chart?
