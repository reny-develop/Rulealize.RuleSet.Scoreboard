# Rulealize.RuleSet.Scoreboard

Points for each player, round after round, and who is ahead. A [Rulealize](https://github.com/reny-develop/Rulealize) rule set.

| | |
| --- | --- |
| Rule set id | `Rulealize.RuleSet.Scoreboard` |
| Package | [`Rulealize.RuleSet.Scoreboard`](https://www.nuget.org/packages/Rulealize.RuleSet.Scoreboard) |
| Inputs | `join`, `score`, `rename`, `leave`, `clear`, `undo` |
| Holds | nothing |
| Draws on | TypeSchema, State, Sequence, Record, Comparison, Logic, Arithmetic, Branch, Binding, Definition |

Whatever the game, players are added, renamed and removed, each score is entered as it comes, and the last one can be taken back. A score may be negative. Removing a player takes their scores with them, and renaming keeps them.

## Opening it

[Rulpane](https://github.com/reny-develop/Rulpane) opens it from the
[Rulealize Registry](https://github.com/reny-develop/Rulealize.Registry) by its identifier and
version: `#r=Rulealize.RuleSet.Scoreboard@1.0.0`.

## License

[Apache-2.0](LICENSE).
