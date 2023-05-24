
# Master GPT

Master GPT is a tool to enhance ChatGPT with prebuilt prompts.

## Description

Master GPT provides a user-friendly menu system that allows users to select preconfigured prompts for interacting with ChatGPT. The prompts are stored in a CSV file, and users can choose from various options to engage in a chat-like conversation with ChatGPT.

## Requirements

To run Master GPT, you'll need the following:

- Python 3.x
- `openai` package (install via `pip install openai`)
- OpenAI API credentials (get your API key from OpenAI)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/master-gpt.git
```

2. Navigate to the project directory:

```bash
cd master-gpt
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Set up your OpenAI API credentials:

Replace `'YOUR_API_KEY'` in the `master_gpt.py` file with your actual OpenAI API key.

## Usage

1. Create a CSV file named `options.csv` in the project directory. (A prebuild csv is included)
2. Add your desired prompts and corresponding actions in the CSV file.
3. Run the script:

```bash
python master_gpt.py
```

4. The main menu will be displayed with the available options.
5. Enter the number corresponding to the desired option and press Enter.
6. Interact with ChatGPT by entering messages.
7. To return to the main menu, type `!menu` and press Enter.
8. To exit the program, choose the option `0` from the main menu.

## Example CSV File Format

The `options.csv` file should have the following format:

```csv
act,prompt
Option 1,Hello, how can I assist you?
Option 2,What is your favorite movie?
Option 3,How is the weather today?
```

Each row represents an option that the user can choose from. The `act` column contains the name of the option, and the `prompt` column contains the initial prompt to be sent to ChatGPT.

## Contributing

Contributions to Master GPT are welcome! If you have any ideas, enhancements, or bug fixes, please submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```

Feel free to modify the content and structure of the README file as per your requirements.