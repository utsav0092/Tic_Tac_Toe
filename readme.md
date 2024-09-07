<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tic-Tac-Toe Game README</title>
</head>

<body>
    <h1>Tic-Tac-Toe Game with AI (Minimax Algorithm)</h1>

<h2>Overview</h2>
    <p>This project implements a classic Tic-Tac-Toe game where a human player competes against an AI that uses the
        Minimax algorithm to play optimally and ensure an unbeatable performance.</p>

<h2>Game Rules</h2>
    <ul>
        <li><strong>Grid:</strong> 3x3 board.</li>
        <li><strong>Human:</strong> Plays as 'O'.</li>
        <li><strong>AI:</strong> Plays as 'X'.</li>
        <li><strong>Win:</strong> Align three symbols in a row, column, or diagonal.</li>
        <li><strong>Tie:</strong> If no winner and board is full.</li>
    </ul>

<h2>AI: Minimax Algorithm</h2>
    <p>The AI uses the Minimax algorithm to evaluate all possible moves and choose the best outcome:</p>
    <ul>
        <li><strong>Win:</strong> +10 points.</li>
        <li><strong>Lose:</strong> -10 points.</li>
        <li><strong>Draw:</strong> 0 points.</li>
    </ul>
    <p>The AI simulates future moves, ensuring it never loses by maximizing its chances of winning or forcing a draw.
    </p>

<h2>Gameplay Flow</h2>
    <ol>
        <li><strong>Human Turn:</strong> The player clicks an empty square to place 'O'.</li>
        <li><strong>AI Turn:</strong> The AI responds with its optimal move using Minimax.</li>
        <li><strong>Outcome Check:</strong> After each move, the game checks for a win or a tie.</li>
        <li>The game ends with a win, tie, or continues if moves remain.</li>
    </ol>

<h2>Future Enhancements</h2>
    <ul>
        <li><strong>Difficulty Levels:</strong> Introduce adjustable difficulty by making the AI play sub-optimally.
        </li>
        <li><strong>Multiplayer Mode:</strong> Add an option for two human players to play without the AI.</li>
    </ul>
<hr />
    <p>For the credit and video overview prefer:- <a href="https://youtu.be/P2TcQ3h0ipQ">Click here</a></p>
</body>

</html>
