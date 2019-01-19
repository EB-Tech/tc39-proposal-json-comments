JSON Comments
=============

Allow comments in JSON data passed to `JSON.parse(…)`.

## Motivation

Comments help annotate configuration or localisation files,
which are stored in the JSON file format.

The fact that they were removed from the JSON specification
simply because Douglas Crockford didn't like them is a terrible
reason, and an [overwhelming majority of web developers agree
that removing them was dumb](https://redd.it/4v6chu).

Many JSON parsers already support comments, with the JSON parser
built into ECMAScript being part of a minority of JSON parsers
that don't support comments.

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
