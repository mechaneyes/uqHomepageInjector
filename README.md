# UQ Homepage Injector

This takes a stream of source files, transforms each file to a string and injects each transformed string into placeholders in the target stream files.

When building homepages, markup and styling need to be conjoined before uploading into the relevant content slot. This becomes tedious, especially toward the end of the dev process where there are little tweaks to both styling and markup which then need to be copied into a separate file before uploading, testing, tweaking, rinsing and repeating.

With this gulpfile the task/command `gulp inject` grabs markup and styling and places them into a single file which I can then copy and paste into Business Manager.

For the relevant code in gulpfile.js, look to line 106.