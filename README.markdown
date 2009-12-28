# Snippet mode for fuzzyfinder.vim

This hack lists the available snippets (via snipMate) for the current file type
in true FuzzyFinder style. Selecting a snippet from the list will then expand
it in kind.

## Screenshot

Example use within a PHP filetype:-

![snippets](http://img15.imageshack.us/img15/4523/fufsnippet.png)

## Requirements

- [snipMate 0.83+](http://www.vim.org/scripts/script.php?script_id=2540)
- [FuzzyFinder 3.5+](http://www.vim.org/scripts/script.php?script_id=1984)

## Installation

- Patch snipMate (snipmate.patch) e.g. `patch -p0 < snipmate.patch`
- Patch FuzzyFinder (fuf.patch) e.g. `patch -p0 < fuf.patch`
- Copy 'snippet.vim' to ~/.vim/autoload/fuf/
- Map something to :FufSnippet e.g. `map <Leader>s :FufSnippet<CR>`

## Contact

- Feel free to message me on github.
