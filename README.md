# kdpy

**kdpy** is an open-source Python utility library designed for developers. The first functionality provided is a decorator to measure the execution time of a specific function.

## Features
- Easy-to-use function execution timer
- Lightweight and dependency-free
- Open-source and developer-friendly

## Installation

You can install `kdpy` using pip:

```sh
pip install kdpy
```

Alternatively, you can install it from the source:

```sh
git clone https://github.com/your-username/kdpy.git
cd kdpy
pip install -e .
```

## Usage

Using `kdpy` to measure function execution time:

```python
from kdpy import measure_time

@measure_time
def example_function():
    for _ in range(1000000):
        pass

example_function()
```

## Development Setup

If you want to contribute or modify the package, follow these steps:

```sh
git clone https://github.com/your-username/kdpy.git
cd kdpy
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -e .
pip install pytest
```

To run tests:

```sh
pytest tests/
```

## Contributing

We welcome contributions! To contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any issues or feature requests, feel free to open an issue on [GitHub](https://github.com/your-username/kdpy/issues).

