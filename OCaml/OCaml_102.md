https://ocaml.org/learn/tutorials/structure_of_ocaml_programs.html

```ocaml
let average a b:
    let sum = a +. b in 
    sum /. 2.0;;
(* val average : float -> float -> float = <fun> *)


let f a b = 
    (a +. b) +. (a +. b) ** 2.0;;
(* val f: float -> float -> float = <fun> *)

let f a b = 
    let sum = a +. b in
    sum +. sum ** 2.0;;
(* val f : float -> float -> float = <fun> *)
```
