# TUM Beamer

![Maintained](https://img.shields.io/static/v1?label=Maintained%3F&message=yes&color=brightgreen)
![Made with LaTeX](https://img.shields.io/static/v1?label=Made%20with&message=LaTeX&color=0076A8&logo=LaTeX)

## Description

This repository template allows to create *TU Munich* presentations using [Beamer] in [LaTeX].

## Getting Started

### Installing
> This `README.md` only covers the setup of using `VSCode` with `Ubuntu` as a subsystem (WSL). If you are using `Windows` only or `macOS`, feel free to update the `README.md` with the necessary steps. This also applies if you are using other IDEs like `Texmaker` or `TexStudio`.

Install [VSCode] with the [LaTeX-Workshop] extension.

On Ubuntu, run:
```cmd
sudo apt-get install texlive-xetex
```
to install [LaTeX] including [XeTeX].

### Building the presentation
From the main path of this repository run:
```cmd
latexmk -xelatex main.tex
```
to build the presentation.

You can also build the presentation in [VSCode] using the `latexmk (xelatex)` recipe of [LaTeX-Workshop].

## Creating a presentation
*tbd*

## Help

If you need any help, please feel free to open an issue in the repository.

## Changelog

Please refer to the [changelog file](./CHANGELOG.md) which documents major changes of this repository.

## Contributing

Please do contribute! Issues and pull requests are welcome.

Please refer to the [contributing file](./CONTRIBUTING.md) for further information how to contribute to this repository.

## Authors

Main contributors:

- veit1337 (<https://github.com/veit1337>)

## License
*tbd*

[VSCode]: https://code.visualstudio.com/
[LaTeX-Workshop]: https://github.com/James-Yu/LaTeX-Workshop
[LaTeX]: https://www.latex-project.org/get/
[XeTeX]: https://wiki.ubuntuusers.de/XeTeX/
[Beamer]: https://github.com/josephwright/beamer/tree/main
