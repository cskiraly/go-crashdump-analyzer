# Go Crashdump Analyzer

A simple tool to visualize the state, stack trace, a dependency graph of goroutines.

![Go Crashdump Analyzer UI](images/go-crashdump-analyzer.png?raw=true "Go Crashdump Analyzer UI")

## Installation

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Usage

Run the analyzer with a crash dump file:

```bash
python crashdump-goroutines.py <crash_dump_file> [-v] [-s <extra_output_file>]
```

Open the generated `goroutine_graph.html` with a browser.
Optionally, specify another static output file with `-s`, e.g. `-s goroutines.svg`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
