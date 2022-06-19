# json2csv

[![npm version](https://badge.fury.io/js/json2csv.svg)](http://badge.fury.io/js/json2csv)
[![Node.js CI](https://github.com/juanjoDiaz/json2csv/actions/workflows/on-push.yaml/badge.svg)](https://github.com/juanjoDiaz/json2csv/actions/workflows/on-push.yaml)
[![Coverage Status](https://coveralls.io/repos/github/juanjoDiaz/json2csv/badge.svg?branch=main)](https://coveralls.io/github/juanjoDiaz/json2csv?branch=main)

Converts JSON into CSV with column titles and proper line endings.  
Can be used as a module from node.js or the browser as well as from the command line.

## Features

- Fast and lightweight
- Support for standard JSON as well as NDJSON
- Scalable to infinitely large datasets (using stream processing)
- Advanced data selection (automatic field discovery, underscore-like selectors, custom data getters, default values for missing fields, 
- Support for custom input data transformation
- Support for custom csv cell formatting.
- Highly customizable (supportting custom quotation marks, delimiters, eol values, etc.)
- Automatic escaping (preserving new lines, quotes, etc.)
- Optional headers
- Unicode encoding support
- Pretty printing in table format to stdout