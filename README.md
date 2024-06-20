# Process Call vs Process Route in Boomi

### Process Call Shape Overview
The Process Call shape enables you to execute another process from within a process. The subprocess that is called, is considered a separate/distinct process execution.

### When to use Process Call Shape
:zap: The Sub-Process doesn't need to be deployed.

:zap: The Sub-Process would not be used by more than 1 Main-Process.

:zap: The Sub-Process is rarely updated.

### Process Route Shape Overview
The Process Route shape allows you to select an execution path dynamically at run time based on some value, such as a document property, data profile, extension value, or trading partner.

### When to use Process Route
:zap: The Sub-Process needs to be deployed.

:zap: The Sub-Process would be used by more than 1 Main-Process.

:zap: The Sub-Process is frequently updated.
