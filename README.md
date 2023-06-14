# Date Processing Functions

This project consists of a collection of functions to process dates. It provides various functionalities related to dates, such as determining the number of days in a month, checking the validity of a date, calculating the number of days between two dates, and calculating the age in days.

## Function Descriptions

### `days_in_month(year, month)`

This function takes in a year and a month as input and returns the number of days in that month. The year should be an integer between `start_datetime` and `end_datetime`, and the month should be an integer between 1 and 12.

### `is_valid_date(year, month, day)`

This function checks if a given date is valid. It takes in a year, month, and day as input and returns `True` if the date is a 'Valid date' and `False` otherwise date is 'Invalid date'. The year, month, and day should be integers representing the corresponding values of the date.

### `days_between(year1, month1, day1, year2, month2, day2)`

This function calculates the number of days between two dates. It takes in the year, month, and day of the first date (year1, month1, day1) and the year, month, and day of the second date (year2, month2, day2). It returns the number of days between the two dates. If either date is invalid or the second date is before the first date, it returns 0.

### `age_in_days(year, month, day)`

This function calculates the age of a person in days based on their birthday. It takes in the year, month, and day of the birthday as input and returns the age in days. If the input date is invalid or in the future, it returns 0.

## Usage

To use these functions, simply import the `datetime` module and the functions from the provided code. Then, you can call the functions with the appropriate input parameters to perform the desired date processing tasks.

```python
import datetime

# ... rest of the code ...
