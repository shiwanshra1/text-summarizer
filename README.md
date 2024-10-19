
# Text Summarizer

This project is a Python-based **Text Summarizer** that processes a block of text and generates a concise summary. The summarizer uses Natural Language Processing (NLP) techniques, including tokenization, stopword removal, and sentence scoring based on word frequencies, to identify the most important sentences from the text.

## Features

- **Text Preprocessing**: Cleans and tokenizes the input text.
- **Word Frequency Calculation**: Computes word frequencies and normalizes them to score importance.
- **Sentence Scoring**: Scores sentences based on word importance.
- **Summary Extraction**: Extracts the top-scoring sentences to create a concise summary of the input text.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/shiwanshra1/text-summarizer.git
    ```
2. Navigate to the project directory:
    ```bash
    cd text-summarizer
    ```
3. Install required dependencies using `pip`:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the script:
    ```bash
    python text_summarizer.py
    ```
2. You will be prompted to input the text you want to summarize.
3. The summarizer will output the summarized version of the text.

## Example

Input:
```
Artificial intelligence (AI) refers to the simulation of human intelligence in machines that are programmed to think and act like humans. The term may also be applied to any machine that exhibits traits associated with a human mind such as learning and problem-solving...
```

Output:
```
Artificial intelligence (AI) refers to the simulation of human intelligence in machines. The ideal characteristic of artificial intelligence is its ability to rationalize and take actions that have the best chance of achieving a specific goal.
```

## Dependencies

- `nltk` (for natural language processing)
- `heapq` (for extracting the top sentences)

Ensure that you have the necessary NLTK datasets downloaded:
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to fork this repo and submit pull requests.

## Contact

For any queries, reach out at:

- **GitHub**: [shiwanshra1](https://github.com/shiwanshra1)
- **Email**: ershiwa91@gmail.com
