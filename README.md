# How to add sounds

1. Create a mp3 file; naming convention: everything lower-case, no special characters, dashes for spaces
2. Add the mp3 file in the `sounds` folder
3. Open the index.html file and add the sound in the `sounds` array. The array has to have two elements, a) the label and b) the person speaking. The label should have a connection to the filename. Example:

The element:
```js
["Not my call", "Mike"]
```

The filename: not-my-call.mp3

If you add a sound from a new person to the collection, you should also "register" the person in the `colors` object with a color of your choice.

That's basically it.