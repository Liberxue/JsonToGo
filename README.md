# Json to Go struct
## Translates JSON into a Go type definition supper grom
Things to note:

- The script sometimes has to make some assumptions, so give the output a once-over.
- In an array of objects, it is assumed that the first object is representative of the rest of them.
- The output is indented, but not formatted. Use `go fmt`!

Contributions are welcome! Open a pull request to fix a bug, or open an issue to discuss a new feature or change.
