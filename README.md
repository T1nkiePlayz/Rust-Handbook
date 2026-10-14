# Rust Handbook

**A visual, deep-dive handbook for learning Rust from absolute zero.**

🔗 **Live site: [rust.handbook.ashtontink.com](https://rust.handbook.ashtontink.com/)**

*Rust from Zero* is a single-page, self-contained guide that takes you from installing Rust all the way through unsafe FFI, with a strong emphasis on the concepts that make Rust unique: ownership, borrowing, lifetimes and fearless concurrency.

## What's inside

21 chapters, 88 annotated code examples, 24 comparison/reference tables and a 14-question self-quiz — all in one file, with no build step.

| # | Chapter | Anchor |
|---|---------|--------|
| 1 | What is Rust, and why should you care? | [`#intro`](https://rust.handbook.ashtontink.com/#intro) |
| 2 | Installing Rust & your first program | [`#setup`](https://rust.handbook.ashtontink.com/#setup) |
| 3 | Variables, mutability & data types | [`#variables`](https://rust.handbook.ashtontink.com/#variables) |
| 4 | Functions & control flow | [`#functions`](https://rust.handbook.ashtontink.com/#functions) |
| 5 | Ownership & borrowing — the heart of Rust | [`#ownership`](https://rust.handbook.ashtontink.com/#ownership) |
| 6 | Lifetimes: keeping references honest | [`#lifetimes`](https://rust.handbook.ashtontink.com/#lifetimes) |
| 7 | Structs, enums & pattern matching | [`#structs`](https://rust.handbook.ashtontink.com/#structs) |
| 8 | Collections & strings | [`#collections`](https://rust.handbook.ashtontink.com/#collections) |
| 9 | Error handling without exceptions | [`#errors`](https://rust.handbook.ashtontink.com/#errors) |
| 10 | Generics & traits | [`#traits`](https://rust.handbook.ashtontink.com/#traits) |
| 11 | Modules, crates & packages | [`#modules`](https://rust.handbook.ashtontink.com/#modules) |
| 12 | Closures & iterators | [`#closures`](https://rust.handbook.ashtontink.com/#closures) |
| 13 | Smart pointers & interior mutability | [`#pointers`](https://rust.handbook.ashtontink.com/#pointers) |
| 14 | Fearless concurrency | [`#concurrency`](https://rust.handbook.ashtontink.com/#concurrency) |
| 15 | Unsafe Rust & foreign function interface | [`#unsafe`](https://rust.handbook.ashtontink.com/#unsafe) |
| 16 | Tooling, testing & documentation | [`#tooling`](https://rust.handbook.ashtontink.com/#tooling) |
| 17 | Performance & how Rust compares to other languages | [`#performance`](https://rust.handbook.ashtontink.com/#performance) |
| 18 | Reading the compiler's mind | [`#errors-decoded`](https://rust.handbook.ashtontink.com/#errors-decoded) |
| 19 | Projects & a realistic study plan | [`#roadmap`](https://rust.handbook.ashtontink.com/#roadmap) |
| 20 | Cheat sheets & glossary | [`#cheatsheet`](https://rust.handbook.ashtontink.com/#cheatsheet) |
| 21 | Test yourself | [`#quiz`](https://rust.handbook.ashtontink.com/#quiz) |

## Features

- **Dark / light theme** — click the toggle or press <kbd>T</kbd>; your choice persists across visits (View Transitions API for a smooth cross-fade).
- **Sticky table of contents** — scroll-spy highlighting via `IntersectionObserver`, with a collapsible drawer on mobile.
- **Reading progress bar** — tracks how far through the handbook you are.
- **Copy-to-clipboard** on every code sample.
- **Expand / collapse all** — open every worked example at once for skimming.
- **Self-quiz** — 14 questions with expandable answers to check your understanding.
- **Responsive, dependency-free** — plain HTML, CSS and JavaScript with zero external assets or frameworks.

## Running locally

No build step. Either open the file directly:

```bash
open docs/index.html        # macOS
xdg-open docs/index.html    # Linux
```

or serve it over HTTP:

```bash
cd docs
python3 -m http.server 8000
# → http://localhost:8000
```

## Deployment

The site is published with **GitHub Pages** from the `main` branch, `/docs` folder, served at [rust.handbook.ashtontink.com](https://rust.handbook.ashtontink.com/) via the custom domain declared in [`docs/CNAME`](docs/CNAME).

> [!NOTE]
> The root-level [`CNAME`](CNAME) file duplicates the same domain and is only needed if you ever switch the Pages source to the repository root. If you change the domain, update **both** files.

## Repository layout

```
.
├── CNAME            # custom domain (root, for a root-based Pages source)
├── README.md
└── docs/
    ├── CNAME        # custom domain used by the live Pages site
    └── index.html   # the entire handbook — HTML, CSS and JS in one file
```

## Contributing

Issues and pull requests are welcome — whether it's a typo, a clearer explanation for a tricky section, or a new example.

## License

No license has been declared for this repository yet. All rights reserved by default — add a `LICENSE` file if you plan to open it up.
