## 🏎️ A Note About Corvettes

You can also use these base building tools to create and modify the Corvettes that were introduced in the Voyagers update.

The important thing to know is that Corvettes are treated the same as standard bases, and are found in the exact same location as standard bases. This is in the following location.

`BaseContext => PlayerStateData => PersistentPlayerBases`

Corvette data has the `BaseType/PersistentBaseTypes` key of `PlayerShipBase`.

An important piece of data to look out for is the `UserData` value that is assigned to the ship data. If this gets lost during the import/export process than it will cause issues.

For this reason, it is more stable to ONLY copy and paste the `Objects` part of the base data, and retain all the rest of the data in your save file to ensure the Corvette is still bound to your player's starship collection.

> **IMPORTANT**: Some tools direct you to the Starships area in the save file for Corvette data. This is NOT the correct data to use for the base building tools. Make sure to double check you are handling the data specified in the location above.
