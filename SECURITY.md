# Security Policy

## Reporting a vulnerability

Please **do not** open a public issue. Email security@ptrnformat.org with:

- what you found and where
- steps to reproduce it
- the version or commit you tested

We aim to acknowledge reports within 7 days and will keep you updated until it's resolved.

## What's in scope

The reference libraries and tools in this organization, and the format itself where its design enables an attack. Because `.ptrn` files are ZIP archives, we're especially interested in problems readers can hit when opening an untrusted file: path traversal, decompression bombs, oversized or malformed JSON, and similar issues.

## Supported versions

While the format is a draft, only the latest release of each project is supported.
