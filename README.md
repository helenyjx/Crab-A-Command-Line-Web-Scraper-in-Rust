# Week 6 mini demo

## Crab command line tool

Crab is a command line web scraping tool written in Rust that allows users to extract data from websites and save it in various formats such as CSV, JSON, and SQL. It uses a CSS selector syntax to specify which HTML elements to extract data from and supports various features such as pagination, authentication, and JavaScript rendering. Crab is designed to be fast and efficient, and it can be used on a wide range of websites, from simple static pages to dynamic single-page applications. Overall, Crab is a powerful and flexible tool for web scraping that can be a great choice for developers and data analysts who prefer to work with command line tools.

## key features of Crab:

1. CSS selector support: Crab allows users to extract data from HTML documents using CSS selectors, which makes it easy to target specific elements on a page.

2. Displaying tag content and attribute values: Crab can display the content of specific HTML tags and attributes, which can be useful for previewing the data that will be scraped.

3. DOM structure visualization: Crab can display the structure of an HTML document in a tree-like form, making it easy to understand the hierarchy of elements on the page.

4. HTTP/POST support: Crab can send HTTP requests to websites, including POST requests, which can be useful for scraping data from forms or other interactive elements on a page.

In addition to these features, Crab also supports various other options, such as customizing the user agent string, specifying a delay between requests, and outputting data in various formats such as CSV, JSON, and SQL. Overall, Crab is a powerful and flexible tool for web scraping that can be a great choice for developers and data analysts who prefer to work with command line tools.

## Install crab

1. Installing from crates.io:

* Make sure you have Rust and Cargo installed on your system. You can check this by running `rustc --version and cargo --version` in your terminal.
* Run the command  `cargo install crab` in your terminal.
* Wait for the installation process to complete. Once it's finished, you should be able to use the crab library in your Rust projects.

2. Installing from sources:

* Clone the crab repository to your local machine using git clone `https://github.com/hopv/crab.git` or download the source code from the project's GitHub page and extract it to a directory of your choice.
* Open a terminal window and navigate to the directory where you've cloned or extracted the crab repository.
* Run the command  `cargo install --path .` or `cargo install --path /path/to/crab/repo/`, depending on your directory structure.
* Wait for the installation process to complete. Once it's finished, you should be able to use the crab library in your Rust projects.

## Usage of Crab

- To print the DOM tree of a website, you can use the following command:

```bash
$ crab <url>
```
This will print the DOM tree of the website at the specified URL.

For example, if you ran the command crab https://www.google.com/, the output might look something like this:

```
html
├── head
│   ├── meta
│   ├── title
│   ├── link
│   ├── script
│   └── ...
└── body
    ├── div
    │   ├── input
    │   ├── button
    │   └── ...
    ├── form
    │   ├── input
    │   └── ...
    ├── span
    │   └── ...
    ├── script
    └── ...
```

- To print the DOM tree of specific tags, you can use the following command:

```bash
$ crab <url> get <css-selector>
```
This will print the DOM tree of all elements that match the specified CSS selector.

For example, if you ran the command crab https://www.google.com/ get input, the output might look something like this:

```
input
├── input
├── button
└── input
```

- Crab also supports several extra options:

```
-e, --expand-url: Prints the absolute URL instead of a relative path.
-h, --help: Prints the help information for Crab.
-n, --no-colors: Displays the DOM tree without colors.
-r, --row: Prints the content of each row of the specified tag.
-V, --version: Prints the version information for Crab.
```

By using these options, you can customize the output of Crab to suit your needs. Overall, Crab is a powerful and flexible tool for web scraping that can be a great choice for developers and data analysts who prefer to work with command-line tools.

