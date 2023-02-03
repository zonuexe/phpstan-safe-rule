# A simplified forked PHPStan rules for thecodingmachine/safe

> **Note**
> This fork shrinks the dependent version of [thecodingmachine/phpstan-safe-rule](https://github.com/thecodingmachine/phpstan-safe-rule) to provide a pure rule with the `DynamicFunctionReturnTypeExtension` removed.

The [thecodingmachine/safe](https://github.com/thecodingmachine/safe) package provides a set of core PHP functions rewritten to throw exceptions instead of returning `false` when an error is encountered.

This PHPStan rule will help you detect unsafe function call and will propose you to use the `thecodingmachine/safe` variant instead.

Please read [thecodingmachine/safe documentation](https://github.com/thecodingmachine/safe) for details about installation and usage.
