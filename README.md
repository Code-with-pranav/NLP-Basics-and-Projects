
# NLP Basics and Experiments

## Overview
This repository contains foundational NLP tasks and incremental implementations toward advanced projects, including a word suggestion system. Each task builds core functionality that can be extended or integrated into larger projects.

## Tasks Overview
### Current Implementations
- **Alignment Algorithms**
  - `add_alignments(l, m)`: Generates all possible alignments for two integers `l` and `m`.
- **Tokenization**
  - `tokenize(s)`: Tokenizes a string into individual tokens.
- **IBM Model Implementation**
  - `IBM_model(f, e, m)`: Computes the probability `P(f | e, m)` for given strings and integers.
  - Assumes `m = l` for simplicity.
- **Word Probability**
  - `word_prob(wf, we_a)`: Returns a fixed probability (e.g., `0.5`) for a pair of words.
- **Corpus Analysis**
  - `get_word_count(word)`: Counts occurrences of a word in a corpus.
  - `n_map(corpus)`: Maps each unique word in a corpus to a unique integer.

### Future Work
- Advanced corpus statistics.
- Model training and evaluation.
- Real-time processing for word suggestion.

## Contributions
Contributions are welcome! Submit pull requests or create issues to discuss ideas.
