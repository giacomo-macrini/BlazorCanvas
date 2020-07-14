# BlazorCanvas

I started this project with the intention of learning/exploring what can be done with Blazor and 2d graphics. I am an old-time videogames lover and I always enjoyed coding small games and prototypes in my spare time.

The repository is divided into numbered subfolders, each one with a single example. 

Every example is also published on GitHub Pages via GitHub Actions using the approach outlined [here](https://www.davideguida.com/how-to-deploy-blazor-webassembly-on-github-pages-using-github-actions/) . 

The `master` branch is used to host the published pages. The main branch is `development`.

- [Example1](https://mizrael.github.io/BlazorCanvas/BlazorCanvas.Example1) shows how to initialize the 2d canvas
- [Example2](https://mizrael.github.io/BlazorCanvas/BlazorCanvas.Example2) shows how to render a sprite and react to the window resize event
- [Example3](https://mizrael.github.io/BlazorCanvas/BlazorCanvas.Example3) shows how to move a sprite on the screen
- [Example4](https://mizrael.github.io/BlazorCanvas/BlazorCanvas.Example4) builds on top of the previous one, refactoring and cleaning up the code
- [Example5](https://mizrael.github.io/BlazorCanvas/BlazorCanvas.Example5) shows how to handle mouse inputs
- [Example6](https://mizrael.github.io/BlazorCanvas/BlazorCanvas.Example6) shows how to animate a sprite. Spritesheets were downloaded from [here](https://luizmelo.itch.io/medieval-warrior-pack-2) and combined using [a custom tool](https://github.com/mizrael/BlazorCanvas/tree/master//tools/AnimatedSpritesProcessor)
- [Example7](https://mizrael.github.io/BlazorCanvas/BlazorCanvas.Example7) shows how to control animations using the keyboard
- [Example8](https://mizrael.github.io/BlazorCanvas/BlazorCanvas.Example8) shows how to use a FSM to control animations and move the character on the screen
- [Example9](https://mizrael.github.io/BlazorCanvas/BlazorCanvas.Example9) refactors the code and introduces the Scene Graph

The goal is to create small examples, built one on top of the other, showing how easy it is to render 2d elements using Blazor. Eventually I might end up writing a full game, it highly depends on how much time I'll have.

Every example will be explained in detail by an article on my [personal blog](https://www.davideguida.com).