CR_CautiousChange
=================
This plugin allows you to highlight a block of code you intend to change and copy it into a comment directly above the starting point.
the idea is to be able to refer to the original copy whilst editing a new version.

Additional Configuration
========================

[Bind the CautiousChange command](http://community.devexpress.com/blogs/rorybecker/archive/2010/10/05/binding-keys-in-coderush.aspx) to a key or your choosing.
@!SurlyDev chose **Ctrl+'**, because it was similar to VB's natural comment key of **'**

Usage
=====

Simply highlight your code and invoke the **CautiousChange** action using whichever key you bound to it.

Bonus Usage
===========

If you invoke the **CautiousChange** Command when the caret is resident on the "**End amendment**" of a previous '**CautiousChange**', this action will remove the generated comment, leaving only your new code.

Future Directions
=================

 * Transition to a CodeProvider
 * Tab to Next CautiousChange
 * CodeIssue - "CautiousChange is incomplete"

Credit
======

Original Idea: [@SurlyDev](http://twitter.com/Surlydev)

Original Author: [Mark Miller](http://devexpress.com/mark) 

VB Translation: [@SurlyDev](http://twitter.com/Surlydev)

Minor Refactoring: [Rory Becker](http://devexpress.com/Rory)
