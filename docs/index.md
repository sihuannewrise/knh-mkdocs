# портал KNHCloud

## Список телефонных номеров

=== "Покровка"
    {{ read_excel('assets/mkdocs_telnum_pokrovka.xlsx', engine='openpyxl') }}

=== "Сретенка"

    {{ read_excel('assets/mkdocs_telnum_sretenka.xlsx', engine='openpyxl') }}

=== "ЛУН-Инвест"

    | Method      | Description                          |
    | ----------- | ------------------------------------ |
    | `GET`       | :woman_mage:{ .heart }     Fetch resource  |
    | `PUT`       | :man: Update resource |
    | `DELETE`    | :woman:     Delete resource |

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

I like play :soccer: after a :beer:
