# Contributing

## Building

To create a `.sublime-package` file for distribution:

```bash
# From the sublime directory
zip -r WrenLSP.sublime-package . -x "*.git*" -x "*.DS_Store" -x "README.md"
```

Install via: `Preferences > Browse Packages...` (place in `Installed Packages/` folder)
