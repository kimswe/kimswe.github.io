---
title:  "Test"
---

{% capture my-include %}{% include test.md %}{% endcapture %}
{{ my-include | markdownify }}

## Nono

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}
