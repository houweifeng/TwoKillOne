# TwoKillOne
This is a chess game named 二打一棋, with an AI. See [百度百科](https://baike.baidu.com/item/%E6%89%93%E7%82%AE%E6%A3%8B/8798807) for game rules.  

The AI is implemented with Monte Carlo tree search.

[Play online!](https://arucil.github.io/games/TwoKillOne/game.html)

# Prerequisites

- Emscripten
- SDL2
- SDL2 image

# Build

Debug:
```shell
emcmake cmake -DCMAKE_BUILD_TYPE=Debug .
emmake make
```

Release:
```shell
emcmake cmake -DCMAKE_BUILD_TYPE=Release .
emmake make
```

# Run

```shell
emrun TwoKillOne.html
```