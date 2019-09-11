# Parse Request Line

in iex we can use tab to auto complete functions - it will show you all the available functions for that. You can also add in `h String.` for example to get some extra help. You could also try it with `h Map.` to get some help with the map function.

= in Elixir is not an assignment rather a matcher

a = 1
 returns 1

 1 = a
 returns 1

 2 = 1
 ** (MatchError)

 a = 2
 returns 2

 2 = a
 returns 2

 ^a = 3
 ** (MatchError)

If you have a variable on the left and a value on the right you can rebind the variable to the value. If you want to compare the two then you need to use the pin operator ^. So in this case we are pattern matching against the variables existing value.

You can also do this with lists

[first, 2, last] = [1,2,3]
first
returns 1
last
returns 3

The 2 is a literal value so it's just comparing this. so we can use this to compare but also extract values
