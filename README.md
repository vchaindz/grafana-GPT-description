# JSON Grafana Dashboard Description Generator using OpenAI GPT-3

This is a simple script that takes a JSON file and uses OpenAI's GPT-3 to generate a markdown formatted description for each title in the JSON structure. The script can be customized to include an optional context which will be fed to the GPT-3 prompt.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

You need to have Python 3 installed along with the following Python packages:

- openai

You can install it with pip:

```
pip install openai
```

### Installing

Clone the repository:

```
git clone https://github.com/username/repository.git
```

## Usage

To run the script, you can use the command-line arguments `--key`, `--file`, and `--context`:

```
python script.py --key your-api-key --file path-to-your-json-file --context "Linux Performance Metrics, Linux operating system usage and processes"
```

If you don't provide these arguments, the script will try to use the `OPENAI_API_KEY`, `JSON_FILE`, and `PROMPT_CONTEXT` environment variables respectively. If any of these is not provided, the script may fail.

The updated JSON will be saved in a new file with '_added' appended to the original file name.


