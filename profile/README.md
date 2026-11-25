<p align="center">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/php-type-language/.github/master/assets/dark.png">
        <img src="https://raw.githubusercontent.com/php-type-language/.github/master/assets/dark.png" alt="PHP Type Language">
    </picture>
</p>

**TypeLang** is a toolkit for the type syntax of PHPDoc: the one you write
in `@param`, `@return` and `@var` for [PHPStan](https://phpstan.org/) and
[Psalm](https://psalm.dev/).

```php
$type = new TypeLang\Parser\TypeParser()
    ->parse('array<non-empty-string, list<User>|null>');
```

| Package | What it does |
|---|---|
| [parser](https://github.com/php-type-language/parser) | Type string to AST |
| [phpdoc](https://github.com/php-type-language/phpdoc) | DocBlock to description and tags |
| [mapper](https://github.com/php-type-language/mapper) | Maps data to objects and back by these types |
| [types](https://github.com/php-type-language/types) | AST nodes |
| [printer](https://github.com/php-type-language/printer) | AST back to a string |
| [reader](https://github.com/php-type-language/reader) | PHP Reflection to AST |

[Documentation](https://typelang.dev) · [Syntax Reference](https://typelang.dev/language)
