# Creating mix project

To create an Elixir project

`$ mix new <name>`

mix tool helps us automate common project tasks - sort of like Ruby's rake tool
use `mix help` to see options.

* Config file is just there to help configure the file
* Lib directory which is where our application code will live
* <name>.exs
* Test folder
* mix.exs which is where our dependencies are kept

## .ex Vs .exs

* .ex files are compiled and then run
* .exs files are interpreted like scripts

* both contain Elixir - most of the time we'll just use .ex

## Coding

Elixir code is always organised in name modules - so files start with defining a module.
It is similar to a class.
Functions are within the module which are similar to Ruby methods.

run our file using...

`elixir lib/servy.ex`

This compiles the code in bytecode in memory and then it runs it on the Erlang virtual machine.

OR

use iex which is Elixirs interactive shell - like erb in Ruby. This just runs the file we specify.

```
& iex
> c "lib/servy.ex"
Hello, Elixir!
```
c comiles and runs the file
OR
```
$ iex lib/servy.ex
Hello, Elixir!
```
using iex interprets the file - this option doesn't know about paths or dependencies.
OR
```
$ iex -S mix
```
This option knows about the project - you can now use your modules and functions. Probably the most versatile option.

```
iex> r Servy
```
recompiles the given module so if you make any changes to the code you can run this and update your module on the go.
