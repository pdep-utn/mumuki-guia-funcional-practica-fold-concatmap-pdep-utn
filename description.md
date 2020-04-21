Como venimos viendo hasta acá, en funcional, definir funciones que trabajen con **listas** es muy simple. 

Además, normalmente contamos con bibliotecas que contienen decenas de ellas. Y Haskell no es la excepción: la biblioteca estandar  Prelude viene con muchas funciones de listas útiles: `map`, `filter`, `all`, `zip`, entre muchas otras. 

Sin embargo, estas y otras tantas funciones, pueden ser definidas en términos de otras dos muy simples: `concatMap :: (a -> [b]) -> [a] -> [b]` y `foldl :: (a -> b -> a) -> a -> [b] -> a` (o algunas de sus variantes). :wink:

Antes de comenzar esta lección leé este [archivo.](https://docs.google.com/document/d/1jSrU7lVMan4nbHBETGqvO5VpqJI0KXVWtH7fqnVASPU/edit)