Ablauf des AM0
```
(1, ε, [], 0, ε)
(2, ε, [2/0], ε, ε)
(3, 0, [2/0], ε, ε)
(4, ε, [1/0, 2/0], ε, ε)
(5, 0, [1/0, 2/0], ε, ε)
(6, 5:0, [1/0, 2/0], ε, ε)
(7, 0, [1/0, 2/0], ε, ε)
(17, ε, [1/0, 2/0], ε, ε)
(18, ε, [1/0, 2/0], ε, 0)
```
P[[prog0]](0)= 0

erzeugt mittels:
```
runhaskell AMx/Interpreter.hs E10/A1b.am0 0
```
