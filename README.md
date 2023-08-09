# Monsieur Biz' Flex recipes

All our recipes are here, no exception. Sometimes they are in the [contrib](https://github.com/symfony/recipes-contrib/) repository as well, as a fallback for our plugins.

## Howto

To use our recipes you just need to add an endpoint in your `composer.json`.

```
composer config --no-plugins --json extra.symfony.endpoint '["https://api.github.com/repos/monsieurbiz/symfony-recipes/contents/index.json?ref=flex/master","flex://defaults"]'
```

Please note that with Sylius you may prefer to use this command instead:
```
composer config --no-plugins --json extra.symfony.endpoint '["https://api.github.com/repos/Sylius/SyliusRecipes/contents/index.json?ref=flex/main","https://api.github.com/repos/monsieurbiz/symfony-recipes/contents/index.json?ref=flex/master","flex://defaults"]'
```

