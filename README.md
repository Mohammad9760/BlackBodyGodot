# BlackBodyGodot
this is a simple modification of the shader from [this repo](https://github.com/zubetto/BlackBodyRadiation).
you can include the shader header and use the BlackBodyRadiation function to calculate color of a blackbody with a temprature.

```
#include "BlackBody.gdshaderinc"
.
.
.
// use it like this
vec4 radiation = BlackBodyRadiation(temprature, true, true); //rgb = chromaticity a = luminance
```

[example](https://t.me/GameDevGeeks/385)
