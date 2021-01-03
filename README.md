# DecryptAi

Presenting a Natural Language Processing model to play Decrypto.

## Game description

Players compete in two teams in Decrypto, with each trying to correctly interpret the coded messages presented to them by their teammates while cracking the codes they intercept from the opposing team.

In more detail, each team has their own screen, and in this screen they tuck four cards in pockets numbered 1-4, letting everyone on the same team see the words on these cards while hiding the words from the opposing team. In the first round, each team does the following: One team member takes a code card that shows three of the digits 1-4 in some order, e.g., 4-2-1. They then give a coded message that their teammates must use to guess this code. For example, if the team's four words are "flower", "candy", "tent", and "son", then I might say "father-sweet-pink" and hope that my teammates can correctly map those words to 4-2-1. If they guess correctly, great; if not, we receive a black mark of failure.

Starting in the second round, a member of each team must again give a clue about their words to match a numbered code. If I get 2-4-3, I might now say, "sucker-prince-stake". The other team then attempts to guess our numbered code. If they're correct, they receive a white mark of success; if not, then my team must guess the number correctly or take a black mark of failure. (Guessing correctly does nothing except avoid failure and give the opposing team information about what our hidden words might be.)

The rounds continue until a team collects either its second white mark (winning the game) or its second black mark (losing the game).
