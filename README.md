# Save Game Free

Save Game Free is a free and simple but powerful solution for saving and loading game data in Unity Game Engine.

[:rocket: Get Save Game Pro](https://github.com/BayatGames/SaveGamePro/)

<p align="center">
	<img src="https://raw.githubusercontent.com/BayatGames/SaveGameFree/master/Assets/BayatGames/SaveGameFree/PressKit/Unity%20Package%20Key%20Images%20-%20Large-01.png" alt="Save Game Free Logo" />
</p>

<!-- TOC -->
* [Save Game Free](#save-game-free)
  * [Features](#features)
  * [Download](#download)
  * [Getting Started](#getting-started)
  * [Resources](#resources)
  * [License](#license)
<!-- TOC -->

## Features

The below features made Save Game Free excellent:

- Cross Platform (Windows, Linux, Mac OS X, Android, iOS, tvOS, SamsungTV, WebGL, ...)
- Auto Save
- Web Support
- Encryption
- Easy to Use
- Simple but Powerful yet

## Download

[:sparkles: Download from Asset Store](https://assetstore.unity.com/packages/tools/input-management/save-game-free-gold-update-81519)

[:rocket: Download the latest version from the Releases section](https://github.com/BayatGames/SaveGameFree/releases/latest)

[:fire: Download the Source Code](https://github.com/BayatGames/SaveGameFree/archive/master.zip)

## Install
You can also add it directly from GitHub on Unity 2019.4+. Note that you won't be able to receive updates through Package Manager this way, you'll have to update manually.

1. open Package Manager
2. click +
3. select Add from Git URL
4. paste https://github.com/MidraLab/SaveGameFree.git?path=/Assets/BayatGames/SaveGameFree/Scripts
5. click Add
## Getting Started

Here is a simple usage of Save Game Free:

```csharp
SaveGame.Save<int> ( "score", score );
```

and the full is:

```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

using BayatGames.SaveGameFree;

public class SimpleUsage : MonoBehaviour {

	public int score;

	void OnApplicationQuit () {

		SaveGame.Save<int> ( "score", score );

	}

}
```

## Resources

[:book: Documentation](http://docs.bayat.io/savegamefree)

[:rocket: Patreon](https://www.patreon.com/BayatGames)

[:sparkles: Write Review](https://www.assetstore.unity3d.com/#!/content/81519)

[:star: Check out Save Game Pro](https://github.com/BayatGames/SaveGamePro/)

[:fire: Forum Thread](https://forum.unity3d.com/threads/released-empireassets-save-game-free.457658/)

[:newspaper: Support and News](https://github.com/BayatGames/Support)

## License

MIT @ [Bayat Games](https://github.com/BayatGames)

Made with :heart: by [Bayat Games](https://github.com/BayatGames)
