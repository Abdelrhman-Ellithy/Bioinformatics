# 🐝 Bioinformatics Project

## 📊 Overview
This project is a bioinformatics toolkit that integrates various scripts to perform specific tasks in DNA and protein sequence analysis. The project includes a user-friendly GUI developed with Tkinter to manage and execute different bioinformatics algorithms.

---

## 🎨 Features
- **Interactive GUI**: A Tkinter-based interface to manage and execute bioinformatics scripts.
- **Modular Design**: Individual scripts handle distinct tasks, making the project modular and easy to extend.
- **Automation**: Simplifies the execution of complex bioinformatics algorithms with a click of a button.

---

## 🌐 Prerequisites
- Python 3.x
- Required Libraries:
  - `tkinter`
  - `subprocess`
  - Additional libraries required by individual scripts.

---

## 🔄 Algorithms

### 1. 🔬 Hemolytic Activity Predictor
**Script**: `hemolytic.py`

Predicts the hemolytic activity of peptides based on sequence data. Useful for analyzing peptide stability and toxicity.

---

### 2. 🎲 FASTA File Processor
**Script**: `Fasta_file_processor.py`

Processes FASTA files to extract and manipulate sequence data. Core operations include parsing and validating DNA or protein sequences.

---

### 3. 🍃 DNA Sequence Translator
**Script**: `DNA_sequence_translator.py`

Translates DNA sequences into corresponding RNA or protein sequences. Supports standard genetic code and custom codon tables.

---

### 4. ⚖️ Exact Match Finder
**Script**: `Exact_match_finder.py`

Locates exact matches of query sequences within a larger genome or dataset. Ideal for small-scale pattern searches.

---

### 5. 🔒 Bad Character Heuristic
**Script**: `Bad_character.py`

Implements the bad character rule of the Boyer-Moore string matching algorithm for efficient pattern searching in large datasets.

---

### 6. 🔎 Indexing
**Script**: `Indexing.py`

Constructs data structures like hash tables or k-mer indices to accelerate sequence retrieval and analysis.

---

### 7. 🔐 Suffix Array Construction
**Script**: `Suffix_array.py`

Builds suffix arrays for genome indexing and string matching. A fundamental tool for efficient pattern matching in bioinformatics.

---

### 8. 🌱 Overlap Graph Generator
**Script**: `overlap.py`

Generates overlap graphs from DNA sequences, which are crucial for sequence assembly and alignment tasks.

---

## 📚 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Abdelrhman-Ellithy/bioinformatics-project.git
   cd bioinformatics-project
   ```
2. Ensure all prerequisite libraries are installed.
3. Run the main GUI script:
   ```bash
   python main.py
   ```
4. Use the buttons in the GUI to execute specific scripts.

---

## 🛠️ Troubleshooting
- Ensure Python is installed and added to your system's PATH.
- Verify the availability of required libraries.
- Check the individual scripts for additional dependencies.

---

## 👨‍💻 Author
-Abdelrahman Ellithy

---

## 🌐 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
