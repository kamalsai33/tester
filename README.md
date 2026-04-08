# tester

Simple starter README with a tiny test-code example.

## Test Code Example (Python)

```python
def add(a, b):
	return a + b


def test_add():
	assert add(2, 3) == 5
```

## Run Tests

1. Install pytest:

```bash
pip install pytest
```

2. Save the code in `test_sample.py`.

3. Run:

```bash
pytest -q
```