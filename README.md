## Gold Earning Methods

- **First Message of Stream**: 5 gold
- **Active Messaging**: 2 gold every 5 minutes
- **Watching Stream**: 1 gold every 5 minutes
- **Clip Submission**: 20 gold per clip (max 2 per stream)
- **Monthly Activity**: 50 gold bonus after being active in 3+ streams

## Commands

| Command | Description | Usage |
|---------|-------------|-------|
| `!gold` | Check your current gold balance | `!gold` |
| `!gamble {N}` | 50% chance to win or lose N gold | `!gamble 10` |
| `!duel {user} {N}` | Challenge another user to a duel for N gold | `!duel @username 20` |
| `!accept` | Accept a pending duel challenge | `!accept` |
| `!daily` | Claim daily reward (1-50 gold, once per stream) | `!daily` |
| `!leaderboard` | View top 3 users by gold | `!leaderboard` |
| `!rank` | Check your rank on the leaderboard | `!rank` |
| `!give {user} {N}` | Give N gold to another user | `!give @username 15` |
| `!rob {user} {N}` | Attempt to rob N gold (20% success rate) | `!rob @username 25` |
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
- 20% success rate
- **Success**: Robber gains N gold, victim loses N gold
- **Failure**: Robber loses N/2 gold, victim gains N/2 gold

### !daily
- Can only be claimed once per stream
- Random reward between 1-50 gold
