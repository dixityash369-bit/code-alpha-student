# Java AI ChatBot

A simple console-based chatbot written in Java. It preprocesses text and matches
keywords against a FAQ knowledge base stored in `faq.txt`.

## Features

- Console-based interactive conversation
- Lowercase conversion and punctuation removal
- Rule-based keyword matching
- Editable FAQ knowledge base

## Requirements

- Java JDK 8 or later

## Build and run

Compile the Java sources from the project directory:

```sh
javac *.java
```

Run the chatbot:

```sh
java main
```

Enter `exit` to quit. Add or edit `keyword=answer` entries in `faq.txt` to
customize the knowledge base.

## Project files

- `main.java` — console application entry point
- `ChatBot.java` — chatbot response logic
- `NLPProcessor.java` — input normalization
- `FAQManager.java` — FAQ file loading and lookup
- `faq.txt` — keyword and answer data
