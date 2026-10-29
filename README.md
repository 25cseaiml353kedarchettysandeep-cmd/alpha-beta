# Alpha-Beta Pruning

## Aim
To find the minimax value of a game tree while pruning branches that cannot affect the final decision.

## Algorithm
1. Start with alpha = negative infinity and beta = positive infinity.
2. At a maximizing node, keep the maximum child value and update alpha.
3. At a minimizing node, keep the minimum child value and update beta.
4. Prune remaining children when alpha is greater than or equal to beta.

## How to run
Requires Python 3.10 or newer. No third-party packages are required.

```bash
python alpha_beta.py
```

## Sample output
```text
Enter 8 leaf values separated by spaces: 3 5 2 9 69 5 23 63
Optimal value: 63
```

## Notes
Alpha-beta pruning returns the same minimax decision as ordinary minimax while potentially evaluating fewer nodes.

## Repository structure
- `alpha_beta.py` — program source code
- `README.md` — aim, algorithm, run instructions, and sample output

> Before submission, run the program on your own computer and capture the actual output. Sample output may vary with user input.


## Captured sample output
See [`output.txt`](output.txt) for a sample console run produced from the included program.


## Output file
See [`OUTPUT.txt`](OUTPUT.txt) for a captured sample run. For interactive programs, output depends on the input entered.
