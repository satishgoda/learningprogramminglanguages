```batch
C:\code\haskell> stack ghci

Note: No local targets specified, so a plain ghci will be started with no package hiding or package options.

      You are using snapshot: lts-15.10

      If you want to use package hiding and options, then you can try one of the following:

      * If you want to start a different project configuration than C:\sr\global-project\stack.yaml, then you can use stack init to create a new stack.yaml for the packages in the current
        directory.

      * If you want to use the project configuration at C:\sr\global-project\stack.yaml, then you can add to its 'packages' field.

Configuring GHCi with the following packages:
GHCi, version 8.8.3: https://www.haskell.org/ghc/  :? for help
Loaded GHCi configuration from C:\\Users\\bugs.bunny\\AppData\\Local\\Temp\\haskell-stack-ghci\\2a3bbd58\\ghci-script
Prelude> 
```

```haskell
Prelude> :set +m

Prelude> let add :: Int -> Int -> Int
Prelude|     add x y = x + y
Prelude|

Prelude> :t add
add :: Int -> Int -> Int

Prelude> putStrLn $ (show (add 2 3))
5
```

- https://stackoverflow.com/questions/8443035/multi-line-commands-in-ghci
