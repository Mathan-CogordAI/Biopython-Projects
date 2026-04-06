# **DNA to Protein Translator**

A simple Python tool that converts DNA sequences into mRNA, protein sequences, and calculates GC content. Built using Biopython library.

## ✨ Features

  * DNA sequence validation (A, T, G, C only)
  * DNA → mRNA transcription
  * mRNA → Protein translation
  * GC content calculation (%)
  * Results export to text file

## 📋 Prerequisites

  * Python 3.6+ ( I used Python version 3.13 but you can use recent versions and the old versions )
  * Biopython library

## 🛠️ Installation

### Clone the repository:

https://github.com/Mathan-CogordAI/Biopython-Projects.git

### Install required library:

pip install biopython


## 🚀 Usage
Run the script:

 * python dna_translator.py
 * Enter your DNA sequence when prompted (e.g., ATGGCCATGGCCGATCG)
 * View results and choose to save to Translational_Results.txt

### Example Output

Welcome to the DNA to Protein Translator!

This tool converts DNA sequences into their corresponding protein sequences with the GC content calculation.

Enter your DNA sequence (A, T , G, C only): ATGGCC

### Results: 
DNA sequence:  ATGGCC

mRNA sequence: AUGGCC

Protein sequence: MA

GC content: 50.00%

Do you want to save the results to a file? (yes/no): yes

Results saved to 'Translational_Results.txt'

## 📁 Output File Format

DNA sequence: ATGGCC

mRNA sequence: AUGGCC

Protein Sequence: MA

GC content: 50.00%


## 🐛 Troubleshooting

  * Invalid sequence error: 
          Use only A, T, G, C characters
  * Module not found:
          Install Biopython with pip install biopython
  * File permission error: 
          Ensure write permissions in current directory

## 🔧 Code Structure

  * dna_translator.py  # Main script with all functionality
  * Translational_Results.txt  # Generated output file
  * README.md         # This file

## 🤝 Contributing

* Fork the project
* Create your feature branch (git checkout -b feature/AmazingFeature)
* Commit your changes (git commit -m 'Add some AmazingFeature')
* Push to the branch (git push origin feature/AmazingFeature)
* Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

Biopython - Powerful bioinformatics library
