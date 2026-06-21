# Security Policy

DeCaf is a local VS Code extension for reading logs. Because logs can contain sensitive information, please do not post private logs, customer data, credentials, tokens, internal hostnames, private IPs, or personal information in public GitHub issues or discussions.

## Supported Versions

| Version | Supported |
| --- | --- |
| 1.0 | Yes |

## Reporting A Security Issue

If you find a security issue in DeCaf:

1. Do not include private logs or real customer data in a public issue.
2. Describe the issue with sanitized examples only.
3. Include the DeCaf version and VS Code version.
4. Include the operating system if it matters.

For now, report security issues through GitHub Issues using sanitized information only:

https://github.com/SquidlyJ/decaf/issues

If a report requires sensitive details, do not publish those details publicly. Open a minimal public issue asking for a private contact path.

## Privacy Expectations

DeCaf is local by design:

- No network calls.
- No telemetry or analytics.
- No AI calls.
- No server or cloud processing.
- No bundled sample logs.
- No log content sent outside VS Code.
- No automatic changes to original log files.

## Handling Log Samples

When sharing examples:

- Replace real emails with `example-user`.
- Replace customer/account names with `example-account`.
- Replace hostnames with `host.example.local`.
- Replace public IPs with documentation-reserved or clearly fake values.
- Remove tokens, credentials, session IDs, device IDs, and user IDs.
