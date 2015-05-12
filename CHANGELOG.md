Change Log
==========

Version 1.4.1 *(2014-10-27)*
----------------------------

 * New: Individual typeface options for the header and days.
 * Fix: Prevent warnings which might have been logged about relayout. 


Version 1.4.0 *(2014-10-14)*
----------------------------

 * New: Styling options for typeface, hiding the header, and specifying a divider.


Version 1.3.0 *(2014-08-08)*
----------------------------

 * New: `setShortWeekdays` method allows supplying alternate day names in accordance
   with `DateFormatSymbols.setShortWeekdays`.


Version 1.2.1 *(2014-06-09)*
----------------------------

 * Fix: Revert to older maven-android-plugin to fix .aar artifact.


Version 1.2.0 *(2014-06-09)*
----------------------------

 * New: Better support for theming the widget.
 * New: Optional smooth scroll support for `selectDate`.
 * Fix: Properly clear highlighted dates when initializing the widget.


Version 1.1.1 *(2014-02-26)*
----------------------------

 * Fix: Ensure cell drawables properly invalidate on state change.
 * Fix: Revert to older maven-android-plugin to fix .aar artifact.


Version 1.1.0 *(2014-01-28)*
----------------------------

 * New: `OnDateSelected` itemClickListener.
 * New: `setSelectedDate` initialization method.
 * New: Multi-date selection and range selection modes.
 * New: `OnDateConfiguredListener` controls which dates are selectable along with
   `OnInvalidDateSelectedListener` when an invalid date selection is attempted.
 * New: Use custom selector states for styling.
 * Fix: Use standalone month name when supported.
 * Fix: Use current calendar's proper first day of week.


Version 1.0.3 *(2013-02-25)*
----------------------------

 * Fix: scroll to selected date after init.


Version 1.0.2 *(2013-02-15)*
----------------------------

 * Fix: Months with no selectable dates are no longer displayed.


Version 1.0.1 *(2013-02-13)*
----------------------------

 * Fix: `NullPointerException` when clicking on day headers.
 * Fix: Better row measurement cachine.


Version 1.0.0 *(2013-01-31)*
----------------------------

Initial release.
