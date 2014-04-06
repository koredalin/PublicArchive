```ruby
require 'redcarpet'
markdown = Redcarpet.new("All kinds of public archives.")
puts markdown.to_html
```

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
## All kinds of public archives