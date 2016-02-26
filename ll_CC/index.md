# It works! ;-)

## Section 1

Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Cras mattis consectetur purus sit amet fermentum. Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Sed posuere consectetur est at lobortis.


## Section 2

Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Donec ullamcorper nulla non metus auctor fringilla. Cras mattis consectetur purus sit amet fermentum. Donec ullamcorper nulla non metus auctor fringilla. Cras justo odio, dapibus ac facilisis in, egestas eget quam.

Vestibulum id ligula porta felis euismod semper. Maecenas faucibus mollis interdum. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante venenatis dapibus posuere velit aliquet.

## Code Syntax Highlighting

#### These languages are built-in

C#:
```csharp
public void Linq32() 
{ 
    double[] doubles = { 1.7, 2.3, 1.9, 4.1, 2.9 }; 
  
    var sortedDoubles = 
        from d in doubles 
        orderby d descending 
        select d; 
  
    Console.WriteLine("The doubles from highest to lowest:"); 
    foreach (var d in sortedDoubles) 
    { 
        Console.WriteLine(d); 
    } 
}
```
HTML:
```html
<head>

<meta charset="utf-8" />
<link rel="shortcut icon" href="favicon.png" />
<title>File Highlight ▲ Prism plugins</title>
<base href="../.." />
<link rel="stylesheet" href="style.css" />
<link rel="stylesheet" href="themes/prism.css" data-noprefix />
<script src="prefixfree.min.js"></script>

<script>var _gaq = [['_setAccount', 'UA-33746269-1'], ['_trackPageview']];</script>
<script src="http://www.google-analytics.com/ga.js" async></script>
</head>
```
CSS:
```css
div {
	color: rgba(255, 0, 0, 0.2);
	background: purple;
	border: 1px solid hsl(100,70%,40%);
}
```
#### These languages are auto-loaded from the `components` folder.

Rust:
```rust
fn find_last_nl(buf: &Vec<u8>) -> usize {
	let iter = buf.iter().rev();
	let len = buf.len();
	if len > 0 {
		for i in 0..len {
			if buf[len - 1 - i] == 0x0A {
				if i+1 < len && buf[len - 2 - i] == 0x0D {
					return len  - i;
				} else {
					return len - i;
				}
			}
		}
	}
	return buf.len();
}
```
Perl:
```perl
 # one element
 $AoA[0][0] = "Fred";
 # another element
 $AoA[1][1] =~ s/(\w)/\u$1/;
 # print the whole thing with refs
 for $aref ( @AoA ) {
     print "\t [ @$aref ],\n";
 }
 # print the whole thing with indices
 for $i ( 0 .. $#AoA ) {
     print "\t [ @{$AoA[$i]} ],\n";
 }
 # print the whole thing one at a time
 for $i ( 0 .. $#AoA ) {
     for $j ( 0 .. $#{ $AoA[$i] } ) {
         print "elt $i $j is $AoA[$i][$j]\n";
     }
 }
```
LOLCODE:
```lolcode
BOTH SAEM ANIMAL AN "CAT"
O RLY?
  YA RLY, VISIBLE "J00 HAV A CAT"
  MEBBE BOTH SAEM ANIMAL AN "MAUS"
    VISIBLE "NOM NOM NOM. I EATED IT."
OIC

COLOR, WTF?
  OMG "R"
    VISIBLE "RED FISH"
    GTFO
  OMG "Y"
    VISIBLE "YELLOW FISH"
  OMG "G"
  OMG "B"
    VISIBLE "FISH HAS A FLAVOR"
    GTFO
  OMGWTF
    VISIBLE "FISH IS TRANSPARENT"
OIC
```
