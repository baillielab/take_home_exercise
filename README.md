## Task

You are provided with a [dataset of 200 DNA sequences](https://github.com/learningmodeloflife/take-home-exercise/edit/main/dna_sequences.json), each 1000 base pairs long. Your task is to analyse these sequences and uncover any interesting patterns or properties. This should take between 15-60 minutes.

### **File Format**

The dataset is stored as a JSON file. Here is the general structure of the file:

```
{
    "num_sequences": 200,
    "sequence_length": 1000,
    "sequences": [
        "ATCG... (sequence 1)",
        "GCTA... (sequence 2)",
        ...
        "TACG... (sequence 200)"]
}

```

### Requirements

Implement a Python script (or jupyter notebook) to analyse the sequences. Your script should:

a. Calculate and report basic sequence statistics:

* Overall GC content distribution
* Dinucleotide frequencies

b. Identify the top 5 most common k-mers (substrings) for k=3, 4, and 5

c. Detect any unusual patterns, such as:

* Palindromic sequences above 20 base pairs in length that include at least 3 of the four bases (A,C,T,G)
* Any other patterns you find interesting or unusual

d. Provide a brief summary of your findings, highlighting any sequences or patterns that stand out.

Your code should be well-commented and efficiently implemented. You are free to use any libraries installable from PyPI, if your code has any specific dependencies beyond base python please include a `requirements.txt` or `pyproject.toml` file in your submission.

## Returning your exercise

Please return either

* an executable python script and write-up file in markdown format (n.b. the University of Edinburgh email system strips attachments with a `.py` extension, therefore please return both files combined in a commonly used archive format, i.e., `.zip`, `.tar`, or `.tar.gz` )
* a jupyter notebook containing both the code and write-up

to [Wilna Oosthuyzen](wilna.oosthuyzen@ed.ac.uk) by **Tuesday, 21st of January 2025, 18:00 UTC**.
