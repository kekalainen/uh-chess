# Chess

A desktop application which can be used for playing chess, storing past games and viewing them move-by-move.

## Documentation

[User guide](documentation/user-guide.md)

[Requirements specification](documentation/requirements_specification.md)

[Architecture description](documentation/architecture_description.md)

[Testing document](documentation/testing-document.md)

[Timesheet](documentation/timesheet.md)

## Releases
* [Week 7](../../releases/tag/viikko7)
* [Week 6](../../releases/tag/viikko6)
* [Week 5](../../releases/tag/viikko5)

## Installation

Start by installing [Python](https://www.python.org/) and [Poetry](https://python-poetry.org/).

Then install the dependencies using the following command:

```console
poetry install
```

Finally, start the application using the following command:

```console
poetry run invoke start
```

## Development

Run unit tests using the following command:

```console
poetry run invoke test
```

Generate a coverage report using the following command:

```console
poetry run invoke coverage-report
```

Run lint checks using the following command:

```console
poetry run invoke lint
```

## Attributions

> Font Awesome Free 5.15.3 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free (Icons: CC BY 4.0)

_SVG icons resized, recolored and converted to PNGs (saved in `src/img/pieces`)._
