# German Driving Theory (Klasse B)

Theory digest for the German driving licence exam, compiled from the official question catalogue (1168 questions). Written in Russian.

## Read online

[perchess.github.io/german-driving-licence](https://perchess.github.io/german-driving-licence)

## Contents

- **index.md** — full theory konspekt, rendered as GitHub Pages
- **fragenkatalog.sqlite** — SQLite database of all official exam questions with answers

## Database

```bash
sqlite3 fragenkatalog.sqlite "SELECT question, correct_answers FROM questions WHERE category = '1.1' LIMIT 5;"
```

Schema: `id, question, answer_a, answer_b, answer_c, correct_answers, category`
