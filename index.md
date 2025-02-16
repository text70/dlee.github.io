<div 
    style="
      position: absolute; 
      color: #0ef7c0; 
      text-shadow: 0 0 6px #0ef7c0, 0 0 12px #0ef7c0;
    "
  >
    <h1 style="font-size: 2.5rem; margin: 0;">
      Welcome to Dallas!
    </h1>
      
  </div>
 
 <br/>
 <br/>
 
## About me::🤓♌⚗️
✅: M.S. 
🔲Working on Ph.D.

```markdown
_highlights_

I like to discover new ways to use programs and molecules. 
Organic Chemistry? You got it!
Linux flavors? Arch, Ubuntu, nixpkgs.
Ask me about my com.
```



## Support or Contact  
⚡[Email](mailto:dlee@d-lee.pro)  
⚡[WhatsApp](https://wa.me/15122178182)  
⚡[BuyMeaCoffee(or🍕)](buymeacoffee.com/d_lee)

## Websites
⚡[Need professional help?](https://consult.d-lee.pro)  
⚡[I'm a real cowboy!](https://www.red-tailedhawkranch.com/) 🐄


⚡ Native Austinite, for real. 


```


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

<section class="color-swatches cf"></section>
<!--<div class="swatch">
    <div class="colorbox" style="background:#ff0000"></div>
    <div class="splitcolorbox">
        <span style="background:#ff0">+10%</span>
        <span style="background:#f0f">+10%</span>
        <span style="background:#0ff">+10%</span>
        <span style="background:#f00">+10%</span>
        <span style="background:#0f0">+10%</span>
    </div>
    <div class="colorname">
        <span class="name-main" data-name="red">red</span>
        <span class="name-hexrgb" data-hex="#ff0000" data-rgb="rgb(255, 0, 0)"></span>
    </div>
</div>-->
