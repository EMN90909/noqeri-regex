# API reference

Regex compilation and matching are host-backed because the portable language does not standardize a regex engine ABI yet. The package bounds patterns and inputs, rejects null handles, and leaves the host responsible for UTF-8 and engine-specific syntax policy.

