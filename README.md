# Language Study Tools

This repository contains a collection of small tools, like scripts and applications, to assist in preparing text and audio for later use during language learning.

Currently only one tools is available:

- g2lt (~ generate bilingual text structure), for example to aid shadowing of dialogues.

## Installation

1. Download the latest **g2lt** ZIP archive from the [Releases](https://github.com/andypeeters/language-study-tools/releases) section.
2. Create a separate folder, e.g. ```~/studytools```
3. Unzip the **g2lt** ZIP file into the newly created folder.
4. (Optional) Add the new folder ```~/studytools``` to the **PATH** environment variable so the tool can be starting without the need to keep referring to the folder name.

## Usage

Look up the lesson XML file you want to generate the bilingual text for, and execute the following command:

```bash
g2lt --input dialogue1.xml
```

The tool will automatically generate **dialogue1.html**.
A shorthand version of the same command:

```bash
g2lt -i dialogue1.xml
```


**NOTE!** Any existing file with the same name will be overwritten without warning.

To list all available options and parameters (either command is possible):

```bash
g2lt
g2lt --help
```

To show the version and license information:

```bash
g2lt --version
g2lt --license
```

## Contributing

Although I don't mind pull requests, for the moment please open an issue first
to discuss what kind of change you would like because currently I'm still looking
which direction I'd like to give to this project.

## License

[AGPL3](https://choosealicense.com/licenses/agpl-3.0/)

<a href="https://github.com/andypeeters/language-study-tools/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/badge/license-AGPLv3-purple"></a>
