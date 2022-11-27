# React Tic Tac Toe with Hooks and Rewind

A react app to play tic tac toe.

We store states for the history of moves, current move number and current player.
The game component passes the handle click function as a prop and when it is called by a square, it rerenders the app and calculates the winner at each render.
The current player state is flipped at end of each move.
The entire history is managed by arrays of 9 elements. When the uses clicks on go to step count, we use the current step count as the indice of array and render the board from that point onwards.

Made along with Scrimba's React course.

Quick start:

```
$ yarn # npm install
$ yarn build # npm run build
````

## Development

Run Webpack in watch-mode to continually compile the JavaScript as you work:

```
$ yarn watch # npm run watch
```

## About Scrimba

At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/allcourses)
- [The Frontend Career Path](https://scrimba.com/learn/frontend)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!
