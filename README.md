#Config


Downloand and install Elm
https://atom.io/packages/language-elm - atom package install instructions

can now use `$ elm-repl` in the CLI to use the REPL

`:exit` to quit!

`$ elm-reactor` build elm projects

`$ elm-make` compiles code to HTML or JS  e.g `$ elm-make Main.elm --output=main.html`

`$ elm-package` to install elm libraries e.g. `$ elm-package install evancz/elm-http` This will add the dependencies to your elm-package.json


#Tutorial

##Values
~I have removed the `>` from the REPL so infact the screen would show
```
> "hello"
"hello"
```


typed directly into repl as seen below.

`"hello"` String (no var)

`++` operator to put strings together

`"hello" ++ " world"`

Maths the same as vanilla JS

Elm makes a distinction between floats and numbers with `/` and `//`

#Functions
Function

```
isNegative n = n < 0
<function>
```
