# Chess Random Ness

Recently I came across [an old tweet of mine](https://twitter.com/potherca/status/1445377701896990727?s=20&t=H_hFXDZdm_d_yZLlEC6lzg)
about [an example of Chessboard.js where both sides are played by `Math.random()`](https://chessboardjs.com/examples/5002)

For fun, I made [a Codepen based on that example](https://codepen.io/potherca/full/zYpzjqX) that is slightly more sped up.

Of course, as these things do, one thing led to another, so I present to you: CRN (Chess Random Ness)

This is basically a more elaborate version of the orignal demo, with some buttons added and some statistics thrown in.

You can see it in action at: https://blog.pother.ca/chess-random-ness/

## Screenshot

![image](https://user-images.githubusercontent.com/195757/160922731-e9ad5d12-a738-46fb-aa97-52db3ff1e323.png)


## Example of (roughly) a thousand runs
|         |                       |         |
| ------- | --------------------- | ------- |
| Wins    | ♚                     |      77 |
|         | ♔                     |      73 |
| Draws   | Insufficient Material |     579 |
|         | Fifty-move Rule       |     230 |
|         | Stalemate             |      60 |
|         | Threefold Repetition  |      28 |
| Total   | Games                 |    1047 |
|         | Draws                 |     897 |
|         | Wins                  |     150 |
|         | Moves                 |  362080 |
| Average | Moves per Game        |     346 |
