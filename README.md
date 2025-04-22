# Go Crashdump Analyzer

A simple tool to visualize the state, stack trace, a dependency graph of goroutines.

## Installation

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Usage

Run the analyzer with a crash dump file:

```bash
./go-crashdump-analyzer <path-to-crash-dump-log> [--graph]
```

Open the generated `goroutine_graph.html` with a browser.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
