JSON Comments
=============

Allow comments in JSON data passed to `JSON.parse(…)`.

## Motivation

Comments help annotate configuration or localisation files,
which are stored in the JSON file format.

## Example

```json
/*
 * Multi-line comment
 */
{
	// Single-line comment
	"foo": "bar"
}
```
