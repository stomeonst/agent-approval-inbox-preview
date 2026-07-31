# Agent Approval Inbox for macOS

A local-first macOS menu bar app that gives scripts and automations a clear human checkpoint before sensitive actions continue.

Your workflow writes pending actions to a local JSON file. Agent Approval Inbox keeps them visible until the user approves, completes, rejects, or snoozes each item, then appends the decision to a local JSONL audit log.

## What the full package includes

* Ready-to-run macOS application
* Complete Swift source code
* Simplified Chinese and English interface
* Required, optional, secure, multiline, and pre-filled fields
* Approve, complete, reject, and snooze operations
* Stable-ID deduplication and urgency sorting
* Local JSON input and append-only JSONL output
* LaunchAgent installation scripts
* Executable core test suite
* English technical documentation and Chinese quick-start guide
* Commercial license for one personal or client end product

No cloud service, account, API key, database, or subscription is required.

## Example workflow contract

The public example in [`examples/action-inbox.json`](examples/action-inbox.json) shows the file contract used to create a bilingual approval card. The full package contains the application, source, tests, packaging scripts, and additional examples.

## Requirements

* macOS 14 or later
* Swift 6 or Xcode 16 only when rebuilding from source

The included application uses local ad-hoc signing. Apple Developer ID signing, notarization, App Store submission, and custom workflow integration are outside the included support scope.

## Commercial source package

The complete package is available for **USD 29** as a one-time purchase.

For purchase or licensing questions, email [Chris](mailto:junad87@gmail.com?subject=Agent%20Approval%20Inbox%20source%20package).

This repository is a public product preview. It does not include the application binary or implementation source, and no license to copy, redistribute, or sell the commercial package is granted here.

