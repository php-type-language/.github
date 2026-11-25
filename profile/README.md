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

<table>
    <tr>
        <th width="300">Package</th>
        <th width="1000">What it does</th>
    </tr>
    <tr>
        <td><a href="https://github.com/php-type-language/parser">parser</a></td>
        <td>Type string to AST</td>
    </tr>
    <tr>
        <td><a href="https://github.com/php-type-language/types">types</a></td>
        <td>AST nodes</td>
    </tr>
    <tr>
        <td><a href="https://github.com/php-type-language/printer">printer</a></td>
        <td>AST back to a string</td>
    </tr>
    <tr>
        <td><a href="https://github.com/php-type-language/reader">reader</a></td>
        <td>PHP Reflection to AST</td>
    </tr>
    <tr>
        <td><a href="https://github.com/php-type-language/phpdoc">phpdoc</a></td>
        <td>DocBlock to description and tags</td>
    </tr>
    <tr>
        <td><a href="https://github.com/php-type-language/mapper">mapper</a></td>
        <td>Maps data to objects and back by these types</td>
    </tr>
</table>

[Documentation](https://typelang.dev) · [Syntax Reference](https://typelang.dev/language)
