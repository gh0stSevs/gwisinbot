## Gold Earning Methods

- **First Message of Stream**: 6 gold (9 for subs)
- **Active Messaging**: 2 gold every 2 minutes (3 for subs)
- **Clip Submission**: 20 gold per clip (max 2 per stream)
- **Monthly Activity**: 50 gold bonus after being active in 3+ streams

## Commands

| Command | Description | Usage |
|---------|-------------|-------|
| `!gold` | Check your current gold balance | `!gold` |
| `!gamble {N}` | 50% chance to win or lose N gold | `!gamble 10` |
| `!duel {user} {N}` | Challenge another user to a duel for N gold | `!duel @username 20` |
| `!accept` | Accept a pending duel challenge | `!accept` |
| `!daily` | Claim daily reward (once per stream) | `!daily` |
| `!leaderboard` | View top 3 users by gold | `!leaderboard` |
| `!rank` | Check your rank on the leaderboard | `!rank` |
| `!give {user} {N}` | Give N*85% gold to another user (15% tax) | `!give @username 15` |
| `!rob {user} {N}` | Attempt to rob N gold (25% success rate) | `!rob @username 25` |
| `!bet {option} {N}` | Bet on an option in the prediction | `!bet A 100` |
| `!bonus {user} {N}` | **(Streamer only)** Give bonus gold to a user | `!bonus @username 100` |


## Command Details

### !gamble
- Must have at least N gold to gamble
- 50% chance to win or lose the amount
- No maximum bet

### !duel
- Both users must have N gold
- Challenger initiates, opponent must `!accept` within 30 seconds
- Winner randomly selected (50/50)
- Winner receives N gold, loser loses N gold

### !rob
- Victim must have N gold
- 25% success rate
- **Success**: Robber gains N gold, victim loses N gold
- **Failure**: Robber loses N*40% gold
