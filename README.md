We have time series data and want to add or change time zone information, If not specified, pandas objects have no time zone. However, we can add a time zone using tz during
creation We can add a time zone to a previously created datetime using tz_localize, We can also convert to a different time zone, Finally, pandas’ Series objects can apply tz_localize and tz_convert to every element
pandas supports two sets of strings representing timezones; however, I suggest using pytz library’s
strings. We can see all the strings used to represent time zones by importing all_timezones
