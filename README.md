# test-isort-action

This repo demonstrates the [`isort-action`][isort-action] Github action.

The `.github/workflows/isort.yaml` action contains an example of both a passing and failing check.

The file `example/fail.py` contains incorrectly sorted imports and will fail the lint, whereas `example/pass.py` is correctly sorted.

[isort-action]: https://github.com/jamescurtin/isort-action
