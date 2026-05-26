# Secure Phrase

A fast, offline passphrase generator for the terminal. It uses the official EFF word lists to create memorable, strong passphrases in a single command.

![demo gif](demo.gif)

## Features

- Generates secure passphrases locally (no network calls).
- Uses the official EFF word lists.
- Simple CLI with an optional word count argument.
- Cross-platform .NET app (Windows, macOS, Linux).

## Installation

```
dotnet tool install -g SecurePhrase.Cli
```

## Usage

```
$ sph [wordCount]
```

- If `wordCount` is omitted, a default is used.

Examples:

```
$ sph
debt-vowel-clash-rebel-kung

$ sph 3
nerd-throb-woven
```

## Notes

- Output uses hyphens between words for readability.
- For maximum security, increase the word count.

## Contributing

Issues and pull requests are welcome. For larger changes, please open an issue first to discuss your idea.

## License

MIT
