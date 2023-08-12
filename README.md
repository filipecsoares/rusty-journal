# Rusty Journal (TODO List App)

This is a simple command-line TODO List application created as a personal project to practice the Rust programming language.

## Features

* List all todos
* Add a todo
* Complete a todo

## Requirements

* Rust (stable version recommended)
* Cargo (recommended)

## Usage

* Clone the repository:

```bash
git clone https://github.com/filipecsoares/rusty-journal
```

* Navigate to the project directory:

```bash
cd rusty-journal
```

* To Build the project:

```bash
cargo build
```

* To add a todo:

```bash
cargo run -- add "Item 1"
```

* To complete a todo (by index):

```bash
cargo run -- done 1
```

* To list all todos:

```bash
cargo run -- list
```

By default, all operations are performed in a file called '.rusty-journal.json' in the home directory. You can use all the commands with the file option to change the default location.

```bash
cargo run -- -j test.json add "Item 1"
cargo run -- -j test.json list
cargo run -- -j test.json done 1
```

### Example

Here's an example of how you can use the application:

* Add a todo

```bash
cargo run -- add "Study Rust"
```

* Complete a todo

```bash
cargo run -- done 1
```
