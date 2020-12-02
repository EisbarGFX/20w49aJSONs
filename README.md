- file `max256.json` includes the new default .json config for making a vanilla world with the importable settings.

- file `max272_bedrock266.json` includes a vanilla world with only two parameters changed: `"height": 272` and `"logical_height": 272`
This file includes a bedrock cieling at y co-ordinate 265/266 for reasons yet undetermined, however I have an inkling as how to change it. Testing will come later.
As far as I can tell, `"height"` registers the maximum build height of that world, in this case a height of 272. The parameter `"logical_height"` I so far have 
not yet discovered its purpose. All I know is that it can either be lower or equal to `"height"`, however any higher and it will cause the game to crash on
generation. It does not seem to have any impact on liquids or the bedrock cieling when set lower than `"height"`.
