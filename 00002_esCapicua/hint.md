Utilizar tanto `foldl :: (a -> b -> a) -> a -> [b] -> a` como `concatMap :: (a -> [b]) -> [a] -> [b]`, cuyo objetivo es realizar una transformación y a su vez aplanar el resultado de ese mappeo.