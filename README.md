# CandyJump

A 2D vertical platformer in Unity. Steer a bouncing candy across procedurally arranged platforms and climb as high as you can. The score follows the highest point reached during the run.

![CandyJump gameplay](https://github.com/user-attachments/assets/2ab2dc62-7875-49e4-ae22-56e4408ce9d3)

## Try it

1. Open the repository root in **Unity 6000.0.27f1**.
2. Open [MainMenu](Assets/Scenes/MainMenu.unity) to start from the menu, or open [mainGame](Assets/Scenes/mainGame.unity) to jump directly into the level.
3. Use the horizontal axis in the editor. On mobile, tilt the device to steer using accelerometer input.

## Code tour

- [Character.cs](Assets/Scripts/Character.cs) handles movement, platform bounces, and height-based scoring.
- [GridGenerator.cs](Assets/Scripts/GridGenerator.cs) generates platform rows as the view scrolls and increases scroll speed with level progression.
- [MovePlatform.cs](Assets/Scripts/MovePlatform.cs) and [BrokenCandy.cs](Assets/Scripts/BrokenCandy.cs) are entry points for platform behavior.

See [LICENSE](LICENSE) for the repository license.
