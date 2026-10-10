# Introduction to Git and GitHub — Calculator Exercises

A learning repository containing simple-interest and yearly-compounding calculator exercises.

## Exercises

| File | Behavior |
| --- | --- |
| `simple-interest.sh` | Integer simple interest: `principal × years × rate / 100` |
| `compound_interest.py` | Final compounded amount: `principal × (1 + rate / 100) ** years` |

The Python output is labeled “compound interest,” but the function returns principal **plus** accumulated interest. Subtract the principal to calculate the interest portion. Neither exercise validates input; the Bash script uses integer arithmetic.

## Run

Use Bash with `expr` for the shell exercise and Python 3 for the Python exercise.

```bash
git clone --branch master https://github.com/YehiaM23/jbbmo-Introduction-to-Git-and-GitHub.git
cd jbbmo-Introduction-to-Git-and-GitHub
bash simple-interest.sh
python compound_interest.py
```

No third-party packages or external services are required. Enter principal, years, and rate when prompted. With principal `1000`, duration `2`, and rate `5`, the Python exercise returns final amount `1102.50`.

## Attribution and guides

The calculator sources credit **Upkar Lidder (IBM)**. This is a course/practice repository; exact additional contributions are not established by this review.

See [CONTRIBUTING.md](CONTRIBUTING.md), [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md), and [LICENSE](LICENSE). Suggested improvements include correcting the compound-output label and adding input validation.
