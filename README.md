<!-- A Project Gutenberg plain-text edition of Herman Melville's Moby-Dick, accompanied by an illustration, hosted for easy reference and reuse. -->

# moby-dick-gutenberg

A repository containing the full text of **Moby-Dick; or, The Whale** by Herman Melville, sourced from [Project Gutenberg](https://www.gutenberg.org/), along with an accompanying illustration.

## About

This repository provides a plain-text copy of Herman Melville's classic novel *Moby-Dick* as made freely available through Project Gutenberg. It is intended as a convenient, version-controlled reference for anyone who needs the full text for reading, research, natural language processing, text analysis, or other projects.

## Project Structure

| File | Description |
|------|-------------|
| `moby-dick.txt` | The complete plain-text edition of *Moby-Dick* from Project Gutenberg |
| `moby-dick-illustration.png` | An illustration related to *Moby-Dick* |
| `README.md` | This file |

## Usage

### Reading the text

You can read the novel directly on GitHub by opening [`moby-dick.txt`](moby-dick.txt), or clone the repository locally:

```bash
git clone https://github.com/farmrecipes67/moby-dick-gutenberg.git
cd moby-dick-gutenberg
```

Then open `moby-dick.txt` with any text editor or reader of your choice.

### Using the text for analysis

The plain-text format makes it straightforward to use in text processing pipelines. For example, in Python:

```python
with open("moby-dick.txt", "r", encoding="utf-8") as f:
    text = f.read()

word_count = len(text.split())
print(f"Word count: {word_count}")
```

## Illustration

The repository includes `moby-dick-illustration.png`:

![Moby-Dick Illustration](moby-dick-illustration.png)

## License

The text of *Moby-Dick* is in the **public domain** in the United States and is freely available via [Project Gutenberg](https://www.gutenberg.org/ebooks/2701). Please review Project Gutenberg's [license terms](https://www.gutenberg.org/policy/license.html) for details on redistribution and usage.

## Acknowledgments

- **[Project Gutenberg](https://www.gutenberg.org/)** for digitizing and making classic literature freely accessible.
- **Herman Melville** (1819–1891) for writing one of the greatest novels in the English language.

---

<sub>This README was auto-generated.</sub>