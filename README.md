# My 4 Favorite Ruby Methods

### each
`Goes through every item inn a list, one by one`
```
[1, 2, 3].each do |num|
  puts num
end
```

### map
`Changes every item in a list and returns a new list`
```
squares = [1, 2, 3].map { |n| n * n }
puts squares
```

### select
`Picks an item that match a condition`
```
evens = [1, 2, 3, 4].select { |n| n.even? }
puts evens
```

### include?
`Checks if a list or string contains a specific item`
```
puts [1, 2, 3].include?(2)  # true
puts [1, 2, 3].include?(5)  # false
```