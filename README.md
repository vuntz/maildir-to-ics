# maildir-to-ics

`maildir-to-ics` is a Python script which scans a
[Maildir](http://en.wikipedia.org/wiki/Maildir) folder, extracts any
`text/calendar` MIME parts, and generates an `.ics` file which can
then be imported into any calendaring system which supports the
[iCalendar](http://en.wikipedia.org/wiki/ICalendar) format.

For example, the resulting `.ics` file could be automatically
published via an HTTP URL from which Google Calendar could take a live
feed.

Additional features:

*   Can ignore events older than a certain number of days, or more
    than a certain number of days in the future.
*   Can automatically add alarms to timed appointments in the future
*   Can fix some (but certainly not all) breakage with existing MIME parts

## Usage

Run `./maildir-to-ics --help` to display usage information.

## Support, bugs, development etc.

Please check the [issue tracker](https://github.com/vuntz/maildir-to-ics/issues)
for known issues, and if yours is not there, please submit it.

If you know how to fix a problem or contribute an enhancement, you are
extremely welcome to [fork this repository](https://github.com/vuntz/maildir-to-ics/fork),
commit your fix, and then send a [pull request](https://help.github.com/articles/using-pull-requests)!

## Author

Vincent Untz &lt;vincent@vuntz.net&gt;

## License

[MIT (Expat) license](http://en.wikipedia.org/wiki/MIT_License) - see
source code for full license.
