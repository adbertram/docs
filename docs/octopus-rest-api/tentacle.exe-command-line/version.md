---
title: version
description: Show the Tentacle version information
---

Show the Tentacle version information

**version options**

```text
Usage: tentacle version [<options>]

Where [<options>] is any of:

      --format=VALUE         The format of the output (text,json). Defaults
                               to text.

Or one of the common options:

      --help                 Show detailed help for this command
```

## Basic examples

This example displays the tentacle version in the default text format:

```
tentacle version
```

This example displays the tentacle version in JSON format:

```
tentacle version --format="json"
```
