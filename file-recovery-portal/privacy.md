# File Recovery Portal privacy policy

Effective date: November 9, 2026

File Recovery Portal is published by MindtheApp. File scanning, recovery and drive copying
take place on your computer. The app does not upload your drive image, recovered files,
preview thumbnails, recovery history or recovery reports as attachments.

## Crash reports

Crash reports are off unless you turn on "Send crash reports" on the app's Home page.
While it is off, the app does not start its crash-reporting client and sends no error
reports. While it is on, the app sends an error report to Sentry when its error handlers
capture an unexpected error. You can turn it off again at any time; the choice is stored
in the app's settings file on your computer. Reports help diagnose software faults.

Reports can contain the error type and message, stack traces, application, SDK, loaded-module
and runtime information, Windows and device diagnostic context, event identifiers,
timestamps and up to 50 diagnostic
breadcrumbs (recent diagnostic events). Automatic session tracking is disabled. The app
does not configure performance tracing, screen recording, screenshots or memory-dump uploads.

Before sending an error event, the app clears the Sentry user field and server-name field.
It replaces occurrences of the current Windows account name in error messages, selected
stack-trace fields and breadcrumb messages. This is not full path removal: file and folder
names, drive letters and other path components can remain in error messages or diagnostic
data. Structured breadcrumb data and other diagnostic context do not go through that text
replacement. Do not assume that all reports are anonymous or that all paths are removed.
The app does not intentionally read file contents for crash reporting, but error text is
sent and can include information supplied by the component that reported the error.

The configured Sentry ingestion address is in its German service region. Sending a report
also exposes the connection's IP address to the receiving service. Default personal-data
collection in the SDK is disabled; that does not prevent the service from seeing a network
connection. This policy does not promise IP-address removal or a particular retention period.

## Optional feedback

Feedback is only sent when you type a message and choose Send in the feedback dialog,
whether or not crash reports are on. Sending feedback does not send error reports while
crash reports are off. The message you enter is sent to Sentry. Leading and trailing
whitespace is removed. The feedback message is not passed through the app's account-name
redaction routine. Any names, paths, email addresses or other information you type may be
included. Do not include private files, passwords or sensitive information. The feedback
form does not ask for your name or email address and does not attach files or screenshots.
When crash reports are off, the reporting client is started only to send that message and is
closed again right after. The reporting client keeps no files on your PC (no offline queue and
no installation identifier) and does not send counts of discarded reports.

## Other data and services

No other outbound data collection was found in this release's application code. The app
does not include advertising, purchases, accounts, public uploads or a file-sharing service.
Windows File Recovery and the Microsoft Store are separate Microsoft products governed by
their own terms and privacy practices. Sentry processes the diagnostic and feedback data
described above for the developer. Local work files, history, settings and mount records
can remain on your computer after uninstalling the app. No offline queue of reports is kept.

## Contact

For a privacy question, use MindtheApp's support contact displayed on the Microsoft Store
listing for File Recovery Portal. Please describe the issue without sending private files.

