Example Crash Reports
=====================

In this directory are crash reports generated by various causes so that you can see what kind if information KSCrash gathers in such situations.
You can cause these crashes from the CrashTester app, included in the workspace.

For each crash I have included the standard KSCrash (JSON) report, as well as an Apple-style report.

Of note:

* Any NSException crashes where the exception references an object will show the contents of that referenced object.
* If the NSException was deallocated for some reason, it will be noted at the top of the Apple report.
* If the crash reporter itself crashed, or the user code called by the crash callback crashes, you'll see a recrash report at the bottom of the main report.
* While CrashDoctor attempts to interpret the report and give a more understandable crash reason, it's not perfect.
