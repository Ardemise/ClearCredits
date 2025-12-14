# Ledger Model

Clear Credits uses an append-only ledger. Balances are calculated from events, not edited directly.

## Core rules
- Credits are issued, redeemed, adjusted, or expired as events
- Events are immutable once written
- Balances cannot go negative
- Every event has a timestamp, actor, and reason
