# Project 7: Package a Rust Script into a Command-Line Tool

This project aims to package a rust script into the command line tool. 

It is modified based on the template project [https://nogibjj.github.io/rust-data-engineering/](https://nogibjj.github.io/rust-data-engineering/) provided by Prof. Noaf.

## Environments

* Works with both AWS CodeCatalyst and GitHub Codespaces

## Main Idea

To package a rust script into the Command-Line Tool package
* Choose one project provided in the template repo
* Modify the main.rs file in the project (here we choose caesar-cipher-cli) to allow input from the terminal and store the output into the output.txt file

## Stpes

* cd to `caesar-cipher-cli` directory
* run `cargo run -- --message "Here goes your message to excrypt" --encrypt --shift 10 --output output.txt` in terminal
* Get the output in output.txt file
