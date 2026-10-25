# DNA Sequence Analyzer

### A Beginner-Friendly Bioinformatics Tool Built with Python and Streamlit

## 📖 About the Project

DNA Sequence Analyzer is a simple web application developed using Python and Streamlit. It allows users to enter a DNA sequence and analyze its nucleotide composition.

This project was created as part of my journey in learning Python programming and exploring how coding can be applied to biology.

## Features

The DNA Sequence Analyzer can:

- Accept DNA sequences entered by the user.
- Convert lowercase DNA sequences to uppercase.
- Validate DNA sequences by checking for A, T, G, and C.
- Calculate the total sequence length.
- Count the number of adenine (A), thymine (T), guanine (G), and cytosine (C) nucleotides.
- Calculate the GC percentage.
- Display an error message for invalid sequences.

## Technologies Used

- **Python 3:** Programming language used for DNA sequence analysis.
- **Streamlit:** Python library used to create the interactive web interface.
- **Google Colab:** Environment used to develop the Python code.
- **GitHub:** Platform used to store and share the project.

## Example Analysis

**Input DNA sequence:**

`ATGCGATCG`

**Expected output:**

| Analysis | Result |
|---|---|
| Sequence length | 9 |
| Adenine (A) | 2 |
| Thymine (T) | 2 |
| Guanine (G) | 3 |
| Cytosine (C) | 2 |
| GC content | 55.56% |

## How GC Content Is Calculated

GC content represents the percentage of guanine (G) and cytosine (C) nucleotides in a DNA sequence.

**Formula:**

GC (%) = [(G + C) / Total sequence length] × 100

For example, if a DNA sequence contains 5 G/C nucleotides out of 10 total nucleotides, its GC content is 50%.

## How to Use the Application

1. Open the deployed Streamlit application.
2. Enter a DNA sequence in the text box.
3. Click **Analyze DNA**.
4. View the sequence length, nucleotide counts, and GC percentage.

**Note:** This version accepts only A, T, G, and C. Ambiguous nucleotide symbols such as N are not supported.

## Run the Project Locally

To run the application on your computer:

1. Download or clone this GitHub repository.
2. Install the required packages:

   `pip install -r requirements.txt`

3. Start the Streamlit application:

   `streamlit run app.py`

4. Open the local URL displayed in the terminal.

## Project Structure

```text
DNA-Sequence-Analyzer/
│
├── app.py             # Streamlit application
├── requirements.txt   # Required Python package
└── README.md          # Project documentation
```

## What I Learned

Through this project, I practiced:

- Python variables and strings
- Conditional statements (`if` and `else`)
- `for` loops
- String methods such as `.upper()` and `.count()`
- Calculating percentages using Python
- Validating user input
- Creating a web application using Streamlit
- Publishing a Python project on GitHub

## Future Improvements

I plan to improve this project by adding:

- AT percentage calculation
- Complementary DNA sequence generation
- Reverse complement generation
- FASTA file upload and analysis
- Nucleotide composition charts

## Conclusion

This project helped me understand how Python can be used to solve simple biological problems. It is my first step toward learning bioinformatics and developing more advanced scientific applications.

---

**Made with Python, curiosity, and an interest in biology! 🧬**
