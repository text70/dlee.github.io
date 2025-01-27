## Welcome to Dallas!   
  

## About me
M.S. 
Working on Ph.D.

```markdown
_highlights_

Going digital 
Python
Webservers
Protein Docking(not Docker)
Linux based
```

## Support or Contact  
[Email]<dlee@d-lee.pro>  
[WhatsApp](https://wa.me/15122178182)

## Websites
[Need professional help?](https://consult.d-lee.pro)  
[I'm a real cowboy!](https://www.red-tailedhawkranch.com/)

> [!NOTE]
> Native Austinite, for real. 


```
<pre>
import { assign, map } from '<a href="https://www.npmjs.com/package/lodash" title="Lodash on npm">lodash</a>';

<a href="https://lodash.com/docs#assign" title="assign documentation">assign</a>({ 'a': 1 }, { 'b': 2 }, { 'c': 3 });
// → { 'a': 1, 'b': 2, 'c': 3 } 
<a href="https://lodash.com/docs#map" title="map documentation">map</a>([1, 2, 3], function(n) { return n * 3; });
// → [3, 6, 9] 
</pre>

{--RUN.ME--}
{-|[`onecompiler`]'<https://onecompiler.com/haskell/437bhe5ds">|-}

data Chemistry a = Chem a deriving (Show)
data Technology a = Tech a deriving (Show)
data Biotechnology a = Bio a deriving (Show)
data MaterialsScience b = Material b deriving (Show)

newtype Bioengineer a b = Bioengineer
  { runBioengineer :: (a -> b) ->
[(Chemistry a, Technology a, Biotechnology a)] -> [MaterialsScience b]
  }

bioengineerInstance :: Bioengineer a b
bioengineerInstance = Bioengineer $ \f inputs ->
  map (\(Chem x, _, _) -> Material (f x)) inputs

transform :: Float -> String
transform x = "Material: " ++ show (x * 2)

-- Example input
exampleInput :: [(Chemistry Float, Technology Float, Biotechnology Float)]
exampleInput = [(Chem 21.0, Tech 29.0, Bio 30.0), (Chem 34.5, Tech 50.0, Bio 6.0)]

main :: IO ()
main = do
  let result = runBioengineer bioengineerInstance transform exampleInput
  print result


```

