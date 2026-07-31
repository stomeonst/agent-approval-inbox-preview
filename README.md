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

The public examples show the same file contract with localized content:

* [`examples/action-inbox.json`](examples/action-inbox.json), Simplified Chinese approval card
* [`examples/action-inbox.en.json`](examples/action-inbox.en.json), English approval card

The full package contains the application, source, tests, packaging scripts, and additional examples.

## Good fit

This package is designed for developers and small teams that already have scripts or automations and need a visible checkpoint before actions such as publishing a release, sending a customer reply, approving a delivery, or confirming a paid operation.

It is a practical fit when you want:

* A local macOS approval queue without a hosted service
* A file based contract that can be written from Python, shell, Node.js, or another local tool
* A durable decision log for later review
* Chinese and English operator interfaces

It is not intended to replace a team ticketing system, cloud workflow platform, or mobile approval service.

## Purchase flow

1. Send a purchase or licensing inquiry by email or through the repository issue template.
2. Confirm the required license scope and whether integration help is needed.
3. Receive the commercial package after payment is confirmed.

## Requirements

* macOS 14 or later
* Swift 6 or Xcode 16 only when rebuilding from source

The included application uses local ad-hoc signing. Apple Developer ID signing, notarization, App Store submission, and custom workflow integration are outside the included support scope.

## Commercial source package

The complete package is available for **USD 29** as a one-time purchase.

For purchase or licensing questions, email [Gang Qu](mailto:stomeonst123@gmail.com?subject=Agent%20Approval%20Inbox%20source%20package).

You can also open a structured [purchase inquiry](https://github.com/stomeonst/agent-approval-inbox-preview/issues/new?template=purchase-inquiry.yml).

This repository is a public product preview. It does not include the application binary or implementation source, and no license to copy, redistribute, or sell the commercial package is granted here.
