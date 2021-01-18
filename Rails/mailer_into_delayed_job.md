## When using mailers add to delayed jobs instead of deliver now

```
```ruby
SomeMailer.delay.contact_us(params)
# not 
SomeMailer.contact_us(params).deliver
```
