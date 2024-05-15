# Good Cop

<img src="good-cop.png" alt="Happy cartoon ruby character wearing a police hat" width="150" align="right" />

Good Cop is a configuration for [RuboCop](https://rubocop.org) that’s been known to be a little more lenient and agreeable than other cops. Just add this line to the top of your RuboCop config file to start using it today.

```
inherit_from: "https://www.goodcop.style/base.yml"
```

If RuboCop goes goblin mode on your code, please [open an issue](https://github.com/joeldrapper/good_cop/issues/new) and let us know.

# Starting a new project?

Copy the folliowing into your `.rubocop.yml` file to get started with a good base configuration.

```yaml
inherit_from:
  - "https://www.goodcop.style/base.yml"

AllCops:
  TargetRubyVersion: 3.3
```

## Tabs

By default, spaces are used for indentation. But I recommend using tabs for better accessibility.

```yaml
inherit_from:
  - "https://www.goodcop.style/tabs.yml"

AllCops:
  TargetRubyVersion: 3.3
```
