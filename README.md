| :zap:        This software is under the BSL-1.0 license, however our parent project currently dosen't have a license   |
|-----------------------------------------|
# EzScript
A programming language that compiles to HTML, written entirely in Python, meant to simplify website coding.  
Heres an example of EzScript:  
```
<title> cool ezscript website
<heading> this is a heading
<text> yo
```
Compiles into:

```
<title>cool ezscript website</title>
<h1 style="font-family: Arial;">this is a heading</h1>
<p style="font-family: Arial;">yo</p>
```

## You can even use Lua via [Fengari!](https://fengari.io/)
```
<initlua>
<lua>
function fengari(x)
  print(x * 2)
end
fengari(4)
<endlua>
```
