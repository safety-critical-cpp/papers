# Safety Critical C++
## ISO C++ Committee Paper Repository

This repository contains ISO C++ committee papers from the [Safety Critical C++ group](https://groups.google.com/d/forum/safety-critical-cpp).

### Guidelines

- Use GitHub Flavored Markdown or [Bikeshed](https://github.com/tabatkins/bikeshed).
- ISO C++ committee papers are numbered; committee members can obtain paper numbers from the [isocpp.org](https://isocpp.org) website. Contact Bryce Adelstein Lelbach for assistance obtaining a paper number.
  - `DNNNNRMX` is the `X`th (where X is an uppercase letter: `A`, `B`, ...) draft of the unpublished `M`th revision of the paper `NNNN`.
  - `PNNNNRM` is the `M`th published revision of the paper `NNNN`.
- Create one directory for each paper, named either `PNNNN_title_of_paper` or `title_of_paper` (if you don't have a paper number). The working draft of the paper should be inside that directory and should be named: `title_of_paper.md` or `title_of_paper.bs`.
- When distributing drafts of the paper or submitting a paper to the ISO C++ committee:
  - Generate an HTML version of the document named `PNNNNRM.html` or `DNNNNRMX.html`.
  - Add the HTML version you generated to git in the paper's directory.
  - `git tag` the commit that adds the HTML version; the tag name should be `PNNNNRM` or `DNNNNRMX`.
- Only change a paper to a "P" right before it is submitted to the ISO C++ committee. We don't want to have any confusion about what exact version of the paper was published.
- Dates and times should use [the ISO IS 8601 format](https://en.wikipedia.org/wiki/ISO_8601), e.g. `YYYY-MM-DD`.
