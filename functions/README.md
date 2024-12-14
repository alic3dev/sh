# Extensions

Files shouldn't have extensions, rely on shebangs (#!) instead.
Files which originally had extensions are symbolically linked for legacy purposes and will be renamed after future refactoring.

# Expectations

These functions are meant to be sourced by other scripts

## Example

```sh
source "$ALIC3_SH_DIR/functions/echoColor"
```
