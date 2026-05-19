Here is a simple Python function example:

```python
def hello_world():
	"""Simple hello world function."""
	print("Hello, world!")


def random_number(min_val=0, max_val=100):
	"""Return a random integer between min_val and max_val (inclusive)."""
	import random
	return random.randint(min_val, max_val)


if __name__ == "__main__":
	hello_world()
	print("Random number:", random_number())
```

