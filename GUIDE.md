# 📖 Guide — How to add & update an utang

Done on **github.com** in the browser. No apps. One line per utang. Type and go.

---

## The format

```
- [ ] Debtor Amount Date note...
```

Example:

```
- [ ] Mark 250 2026-06-14 lunch
```

| Part       | What to type                                              |
|------------|-----------------------------------------------------------|
| `- [ ]`    | An **unpaid** utang. Change to `- [x]` once it's **paid**. |
| **Debtor** | Who owes you, one word: Dann / Dustin / Aldwin / Mark.    |
| **Amount** | Pesos, numbers only: `250`.                               |
| **Date**   | `YYYY-MM-DD`, e.g. `2026-06-14`. Use today's date if new. |
| **note**   | Short reason (lunch, jeep, load). Optional.               |

> Order matters: **debtor → amount → date → note**. Keep it on one line.

---

## ➕ Add a new utang (someone owes YOU)

1. Open **your own** ledger (e.g. `ledgers/dann.md`) → click the **✏️ pencil**.
2. Type a new line at the bottom:
   ```
   - [ ] Mark 300 2026-06-14 snacks
   ```
3. **Commit changes** (message like `Mark owes 300`). Done. ✅

---

## 💰 Mark it paid

Change the box from empty to `x`:

```
- [ ] Mark 300 2026-06-14 snacks      ← unpaid
- [x] Mark 300 2026-06-14 snacks      ← paid ✅
```

Don't delete the line — a paid line is your receipt.

---

## Rules recap

- Only edit **your own** file (utangs owed to you).
- Only the lender flips a box to `[x]`.
- Don't delete lines — keep the history.
