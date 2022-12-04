# Online Pony Events During the COVID-19 Pandemic

This dataset documents the various online events in the brony/*My Little Pony: Friendship is Magic* fandom that have taken place from 2020 to 2022, mainly in response to the COVID-19 pandemic.

The dataset is also available as a [Google Sheets spreadsheet](https://docs.google.com/spreadsheets/d/1FQ3Jcje9d7Uq3ZsbXYXfWsozFFxMxqDPxie7MajOZRs/edit).

## Scope

This dataset covers all events that have taken place primarily online in the brony fandom from 2020 to 2022 (formally, having an official start time between 31 December 2019 at 12:00 UTC and 1 January 2023 at 12:00 UTC).

## Format

The dataset consists of two data files:

* `Events.csv`: The list of events
* `Special Mentions.csv`: Related resources that may be of interest

The data files are CSV (mostly following [RFC 4180](https://tools.ietf.org/html/rfc4180), except non-ASCII characters may be introduced as UTF-8) with headers.

## Dates and Times

The events list contains times in UTC and "as stated." "As stated" times are the times announced in publications and social media, which are often not in UTC.

UTC timestamps use an "almost ISO 8601" format for convenience. In this format, the "T" that separates the date and time is replaced with a space, and the "Z" is only implied. "As stated" timestamps strictly follow ISO 8601 format and include the UTC offset.

For events that have only announced dates and not actual times, both the UTC and "as stated" timestamps include only the date (with no offset). Importantly, a date alone does necessarily mean that the time is between 00:00 and 23:59 UTC on that date.

## License

All information in this dataset is dedicated to the public domain under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). (A copy is available in `LICENSE.txt`.) By contributing additional information you agree to the same dedication for your contributions.