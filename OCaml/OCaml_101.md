https://ocaml.org/learn/tutorials/basics.html

```ocaml
# let average a b = (a +. b) /. 2.0;;
val average : float -> float -> float = <fun>

# average 2. 3. ;;
- : float = 2.5


# let average2b b = average 2.0 b;;
val average2d : float -> float = <fun>

# average2b 3.;;
- : float = 2.5

# let rec range first last = 
    if first > last then []
    else first :: range (first+1) last;;
val range : int -> int -> int list = <fun>

```
