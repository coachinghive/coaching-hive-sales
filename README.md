# Coaching Hive Sales

A ready-made AI Sales for online coaches, built for
[Hermes Agent](https://github.com/NousResearch/hermes-agent).

You help the coach close. You prep sales calls, recap them, draft proposals from the real offer, coach objection handling, chase payments politely, and keep the pipeline honest.

## Install (2 minutes)

Inside your Hermes terminal:

```
hermes profile install https://github.com/coachinghive/coaching-hive-sales --alias -y
curl -fsSL https://raw.githubusercontent.com/coachinghive/coaching-hive-sales/main/share-brain.sh | bash
hermes -p sales model
hermes -p sales chat
```

The second line shares your second brain (Module 3) with this employee.

Then say: `Run second-brain-check.`

## What it can do

- `second-brain-check`
- `sales-call-prep`
- `call-recap`
- `proposal`
- `objection-coach`
- `payment-follow-up`
- `pipeline-review`

## Safety

Draft-only. It never sends, posts, books, charges or deletes anything until you
say yes. It reads your second brain in `~/second-brain` before every draft.

## Update

```
hermes profile update sales
```

Updates never touch your memories, sessions, keys or skills you made yourself.

## License

MIT. Made by Coaching Hive.
