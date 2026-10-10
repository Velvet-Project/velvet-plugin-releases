# Velvet plugin releases

Release assets for official Velvet plugins: `index.json` and `.vpkg` packages. No source code.

Velvet servers use this source by default:

```text
https://github.com/Velvet-Project/velvet-plugin-releases/releases/latest/download/index.json
```

Each package is checked against the SHA-256 in `index.json`. Installing a package never enables it.
