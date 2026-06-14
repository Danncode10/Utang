# 💸 Utang Tracker

A dead-simple, no-app, no-database way for the 4 of us to track utangs.
Everything lives as plain Markdown files in this repo. Edit them right here on GitHub.

## 👥 Who's in

Dann · Dustin · Aldwin · Mark

## 📒 The ledgers

Each person has **their own file** for utangs they are owed (i.e. utangs *they* made).

| Person | Ledger |
|--------|--------|
| Dann   | [ledgers/dann.md](ledgers/dann.md)     |
| Dustin | [ledgers/dustin.md](ledgers/dustin.md) |
| Aldwin | [ledgers/aldwin.md](ledgers/aldwin.md) |
| Mark   | [ledgers/mark.md](ledgers/mark.md)     |

## 📜 The rules

1. **You only edit your own ledger file.** If Mark owes Dann, it goes in **Dann's** file, and **only Dann** edits its status.
2. **Only the lender changes the status.** Don't mark your own debt as paid in someone else's file — let them do it.
3. **Don't delete rows.** When something's paid, just change the status to ✅ Paid. Keeps the history honest.
4. **One row = one utang.** Don't combine multiple debts into one line.

## ➕ How to add an utang

See **[GUIDE.md](GUIDE.md)** for the exact format and a step-by-step.

## ✅ Why this works

- 100% free, no Supabase, no database, no deploy.
- Every change is a git commit — free audit trail of who changed what and when.
- Separate files per person = no edit conflicts.
