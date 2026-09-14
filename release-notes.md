# Release Notes

This page provides notes about recent releases.

## 1.1.11

**Released:** September 14, 2026

* A variation in ZipRecuriter emails is not accounted for, making all known variations parsable.
* The 'Date Recieved' column now sorts correctly by time as well as date.
* The 'Last retrieved' date and time is now 'Last refreshed' and only contains the time.

## 1.1.10

**Released:** September 7, 2026

### Enhancements and Fixes

* Refresh of the jobs list now happens on a 30-minute cycle. That cycle is explicit to the user via refresh time.
* Made the loading of new jobs more obvious to users.
* The buttons in the 'Actions' column now aligns correctly with the rest of the 'Jobs' table.
* The 'Actions' column no longer appears sortable.

## 1.1.9

**Released:** August 31, 2026

### Enhancements

* Now parsers emails from _ZipRecruiter_.
* The jobs list loads faster.
* Fixed the display of the extension icon in the jobs list header.
* Fixed rendering of visible text so that non-word characters display correctly.

## 1.1.8

**Released:** August 24, 2026

### Enhancements

* Job titles now wrap to multiple lines so that the whole job title may be read.
* Job Search Monitor now processes emails from _Builtin_ and _Hiring Cafe_.
* Email parsers now handle emails from match.indeed.com in addition to jobalert.indeed.com.
* For convenience, an additional refresh button was added near the job title configuration options.

## 1.1.7

**Released:** August 13, 2026

All change are internal.

## 1.1.1

**Released:** August 5, 2026

### Enhancements and Fixes

* Sender email addresses were reduced to domains to make them more flexible. A second LinkedIn domain was added.
* A 'Share' button was added.
* The 'Donate' button was changed to 'Tip jar'.
* Column widths were adjusted to account for text that takes up too much space. This was done as a temporary fix for the LinkedIn issue. (See below.) It is being kept to prevent future problems.
* A subtle highlight now appears over whichever row contains the mouse pointer.
* A signal now alerts the user to refresh the 'Jobs list' after a job title has been added.

### Known Issues

Some LinkedIn emails are not rendering correctly. This is believed to be a temporary problem caused by LinkedIn.
