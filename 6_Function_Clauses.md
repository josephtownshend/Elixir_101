# Function Clauses

Elixir can do pattern matching on Functions which is called function clauses

```
def route(conv) do
  route(conv, conv.path)
end

def route(conv, "/wildthings") do
  %{ conv | resp_body: "Bears, Lions, Tigers"}
end

def route(conv, "/bears") do
  %{ conv | resp_body: "Teddy, Smokey, Paddington"}
end
```

First function gets called and looks for the next function that matches and runs that one.
