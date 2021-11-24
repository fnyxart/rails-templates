## Rails Templates for Clever Cloud

Quickly generate a rails app with custom templates and [Clever Cloud](http://clever-cloud.com/) configuration. To be revisited.

### Minimal

Get a minimal rails 5.1+ app ready to be deployed on Clever Cloud with Bootstrap, Simple form and debugging gems.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/fnyxart/rails-templates/master/clever_cloud/minimal.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```

### Devise

Same as minimal **plus** a Devise install with a generated `User` model.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/fnyxart/rails-templates/master/clever_cloud/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```
