# Project Status

Limited Underground Business is in active pre-release development. This page is a
plain-language public summary; it is not the private engineering plan or a
production-readiness certification.

## Free-use transition

A Free distribution without subscription, activation key, or trial expiry is in
validation. It has not been publicly released or approved for production use.
The currently downloadable installer remains the historical trial described below.
Final free-use/no-resale terms, independent testing, and owner release approval remain open.

## Current public preview

Version `0.3.0-preview.78` is available as an unsigned, self-contained Windows
x64 seven-day public trial.

The preview includes:

- Selectable business templates and optional modules
- Local users, roles, permissions, inactivity locking, and activity history
- Customers, leads, catalog, inventory, suppliers, and purchase orders
- Quotes, estimates, invoices, payments, expenses, point of sale, jobs, work
  orders, appointments, employee time, fleet, and dispatch workflows
- Business documents and dashboards, including PDF output and a protected
  custom-reporting foundation
- Customer CSV/XLSX import with mapping and review before committing records
- Verified backup, restore, local data export, and privacy-conscious support
  diagnostics
- Twelve interface languages

The exact preview.77-to-preview.78 installer lifecycle passed interrupted-upgrade
recovery, application launch, creation of a fresh version-scoped seven-day
trial, uninstall cleanup, and business-data preservation. The full Release gate
passed with zero warnings and errors across all 23 projects, all 12 interface
languages, and the complete functional and Windows suites.

## Trial boundary

- The trial lasts seven continuous days from first launch for each exact
  version.
- A newer version receives a new seven-day period.
- Reinstalling the same version does not reset that version's period.
- Trial history and business data survive upgrade and uninstall.
- After expiration, signed-in authorized users retain verified backup and
  open-data export access; normal application workflows are unavailable.

## Important current boundaries

- The installer is unsigned, so Windows can identify it as coming from an
  unknown publisher.
- The preview is not approved for production business records or regulated
  workflows.
- Independent clean-machine and real-business acceptance are still required.
- Cloud synchronization, centralized multi-computer operation, Active
  Directory authentication, and external service integrations are future
  capabilities rather than current production claims.
- Final free-use/no-resale terms and support policies remain under review.

## What must happen before a production release

- Complete independent tester acceptance on supported Windows environments
- Finish usability and accessibility review with realistic populated data
- Complete code signing and publisher-identity setup
- Finalize free-use/no-resale terms, support, update, and privacy policies
- Complete legal and regulated-industry review for any claimed specialized
  business use
- Complete final production acceptance

## Public release policy

A source-code change is not automatically a public release. A version appears
on this repository's Releases page only after the exact package is built,
validated, reviewed for public distribution, and accompanied by its checksum
and release notes.
