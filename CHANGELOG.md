# Changelog

## 0.5.4 (Jul 12, 2017)

- Add renderDays event.
- Add maxView and minView control startView mode.


## 0.5.3 (May 30, 2017)

- Highlight the current year and month.
- Highlight the picked year and month.


## 0.5.2 (Apr 8, 2017)

- Fixed year and month picking issue.


## 0.5.1 (Mar 25, 2017)

- Hide the picker when the target input element is blurred (#54).
- Hide the picker when click the trigger element again.
- Fixed some issues in inline mode.


## 0.5.0 (Feb 11, 2017)

- Added a new option `highlightedClass` for highlight today (#28).
- Fixed the position of picker panel (#49).


## 0.4.0 (Oct 15, 2016)

- Rename `autoshow` option to `autoShow`.
- Rename `autohide` option to `autoHide`.
- Rename `autopick` option to `autoPick`.
- Improved the priority of language options.
- Fixed the issue of date view updating (#33).


## 0.3.1 (Jan 11, 2016)

- Fixed the issue of `startDate` option (#20)


## 0.3.0 (Dec 15, 2015)

- Change the default value of `zIndex` option from `1` to `1000`
- Simplify JavaScript code
- Optimize CSS code styles


## 0.2.2 (Dec 10, 2015)

- Fixed the issue of options overriding (#15)
- Fixed the error of next view month


## 0.2.1 (Oct 26, 2015)

- Fixed the error of month picker


## 0.2.0 (Oct 18, 2015)

- Supports custom events
- Supports to set start view date and end view date
- Improved i18n (internationalization)
- Improved placement of the datepicker
- Improved template


### Options

- Added 10 options: `autoshow`, `autopick`, `offset`, `language`, `startDate`, `endDate`, `mutedClass`, `show`, `hide`, `pick`
- Renamed `autoclose` to `autohide`
- Renamed `dateFormat` to `format`
- Renamed `viewStart` to `startView`
- Renamed `showMonthAfterYear` to `yearFirst`
- Renamed `selectedClass` to `pickedClass`
- Renamed `isDisabled` to `filter`


### Methods

- Added 11 methods: `pick`, `reset`, `getMonthName`, `getDayName`, `getDate`, `setDate`, `setStartDate`, `setEndDate`, `parseDate`, `formatDate`, `destroy`
- Removed 2 methods: `enable`, `disable`


### Events

- Added 3 events: `show.datepicker`, `hide.datepicker`, `pick.datepicker`


## 0.1.0 (Aug 9, 2014)

- Fixed some bugs
- Added i18n files
- Optimized code style


## 0.1.0-beta (Feb 14, 2014)

- Supports 21 options: `date`, `dateFormat`, `disabledClass`, `selectedClass`, `autoclose`, `inline`, `trigger`, `container`, `showMonthAfterYear`, `zIndex`, `viewStart`, `weekStart`, `yearSuffix`, `days`, `daysShort`, `daysMin`, `months`, `monthsShort`, `itemTag`, `template`, `isDisabled`
- Supports 5 methods: `show`, `hide`, `enable`, `disable`, `update`
