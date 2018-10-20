### chronic
---

https://github.com/mojombo/chronic

---
https://github.com/mojombo
https://github.com/mojombo/god
https://github.com/mojombo/grit
http://tom.preston-werner.com/

```
gem install chronic

Time.zone = "UTC"
Chronic.time_class = Time.zone
Chronic.parse("June 15 2006 at 5:45 AM")
Thu, 15 Jun 2006 05:45:00 UTC +00:00

```

```ruby
require 'chronic'
Time.now
Chronic.parse('tomorrow')
Chronic.parse('monday', :context => :past)
Chronic.parse('this tuesday 5:00')
Chronic.parse('this tuesday 5:00', :ambiguos_time_range => :none)
Chronic.parse('may 27th', :now => Time.local(2000, 1, 1))
Chronic.parse('may 27th', :guess => false)
Chronic.parse('6/4/2012', :endian_precedence => :little)
Chronic.parse('INVALID DATE')

```

```
```

