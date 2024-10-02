
### Date Formats:
- `d`: Day of the month (two digits, leading zeros) (e.g., 01 to 31).
- `D`: A textual representation of a day (three letters) (e.g., Mon to Sun).
- `j`: Day of the month without leading zeros (e.g., 1 to 31).
- `l`: A full textual representation of the day of the week (e.g., Sunday to Saturday).
- `N`: ISO-8601 numeric representation of the day of the week (e.g., 1 for Monday, 7 for Sunday).
- `S`: English ordinal suffix for the day of the month (e.g., st, nd, rd, th).
- `w`: Numeric representation of the day of the week (e.g., 0 for Sunday, 6 for Saturday).
- `z`: The day of the year (starting from 0) (e.g., 0 to 365).

### Week Formats:
- `W`: ISO-8601 week number of the year (e.g., 42 is the 42nd week of the year).

### Month Formats:
- `F`: A full textual representation of a month (e.g., January to December).
- `m`: Numeric representation of a month (two digits, leading zeros) (e.g., 01 to 12).
- `M`: A short textual representation of a month (three letters) (e.g., Jan to Dec).
- `n`: Numeric representation of a month, without leading zeros (e.g., 1 to 12).
- `t`: Number of days in the given month (e.g., 28 through 31).

### Year Formats:
- `L`: Whether it's a leap year (1 if it is a leap year, 0 otherwise).
- `o`: ISO-8601 year number. This has the same value as `Y`, except that if the ISO week number (W) belongs to the previous or next year, that year is used instead.
- `Y`: A full numeric representation of a year (four digits) (e.g., 2024).
- `y`: A two-digit representation of a year (e.g., 99 or 20).

### Time Formats:
- `a`: Lowercase ante meridiem and post meridiem (am or pm).
- `A`: Uppercase ante meridiem and post meridiem (AM or PM).
- `g`: 12-hour format of an hour without leading zeros (e.g., 1 to 12).
- `G`: 24-hour format of an hour without leading zeros (e.g., 0 to 23).
- `h`: 12-hour format of an hour with leading zeros (e.g., 01 to 12).
- `H`: 24-hour format of an hour with leading zeros (e.g., 00 to 23).
- `i`: Minutes with leading zeros (e.g., 00 to 59).
- `s`: Seconds with leading zeros (e.g., 00 to 59).
- `v`: Milliseconds (e.g., 654).
- `u`: Microseconds (e.g., 654321).

### Full Date/Time Formats:
- `c`: ISO 8601 date (e.g., 2024-10-02T16:23:48+00:00).
- `r`: RFC 2822 formatted date (e.g., Wed, 02 Oct 2024 16:23:48 +0000).
- `U`: Seconds since the Unix Epoch (January 1 1970 00:00:00 GMT).

You can combine any of these to format the date and time however you'd like!