Tequiz
======

```
                           <! . . . . . . . . . .!>
                           <! . . . . . . . . . .!>
 Which one is not a        <! . . . . . . . . . .!>  ↑ / k: rotate
 planet?                   <! . .╭──────────╮ . .!>  ← / h: move left
                           <! . .   locked    . .!>  → / l: move right
 1. Mercury                <! . .╰──────────╯ . .!>  ↓ / j: move down
                           <! . . . . . . . . . .!>      r: reset
 2. Mars                   <! . . .[][][] . . . .!>
                           <! . . .[] . . . . . .!>
 3. Pluto                  <! . . . . . . . . . .!>
                           <! . . . . . . . . . .!>
 4. Venus                  <! . . . . . . . . . .!>
                           <! . . . . . . . . . .!>
                           <! . . . . . . . . . .!>
                           <! . . . . . . . . . .!>
                           <! . . . . . . . . . .!>  [SCORE:       52]
                           <! . . . . . . . . . .!>
                           <! . . . . . . . . . .!>  [LEVEL:        0]
                           <! .[] . . . . . . . .!>
                           <![][][][] . . . . .[]!>  [LINES:        1]
                           <!********************!>
                             \/\/\/\/\/\/\/\/\/\/

```

Tetris was the very first programming project I finished in 2002-2003.
Back then I used C# and it was a GUI application running in Windows.

Recently I watched the movie [Tetris]. When I saw tetrominoes were rendered as
`[]` in the early versions, I was like: "Beautiful!".

So, after 20 years, I want to implement the game one more time, and make it
a TUI application.


## Fun fact:

> The game has monochrome graphics, and in the first revision of the game, the
> blocks in the tetrominos are represented by a pair of delete/rubout
> characters (character code 177); however, the rendering of this character
> code as a rectangle was a feature specific to the Soviet clone machines, an
> actual PDP-11 would instead display nothing. A later revision was made where
> the blocks are represented by a pair of square brackets instead.
>
> -- <cite>https://tetris.wiki/Tetris_(Electronika_60)</cite>


[Tetris]: https://en.wikipedia.org/wiki/Tetris_(film)
