# cloudy-with-a-chance-of-aws

Just having fun with AWS CloudFormation ;)

```ruby
ruby -ryaml -rjson -e 'puts JSON.pretty_generate(YAML.load(ARGF))' < cwacoaws-app.cfn.yml > cwacoaws-app.cfn.json
```
