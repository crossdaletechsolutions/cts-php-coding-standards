# PHP Coding Standards

## Rulesets

### CTS-Coding-Standards

Follows Wordpress-Extra with the following modifications:

- Minimum PHP version required is 7.4.
  - Currently this is not compatible with PHP 8+
- Minimum Wordpress version required is 5.4.
- Enforeced Yoda conditions are not.
- Strict Equality is enforced.
- Strict Ternary is allowed.
- Strict types should be enabled.
- Short array syntax is now preferred.
- All global variables and functions should be prefixed with either `cts` or `crossdale`.
- All namespaces should start with `Crossdale`.
- All translation functions must use `crossdale` namespace.

## Installation

Verify the repository where this is going to be installed has at least the following keys in `composer.json`:

```json
	"repository": [
		{

		}
	]
```
