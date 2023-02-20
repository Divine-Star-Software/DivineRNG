<h1 align="center">
  Divine RNG
</h1>


<p align="center">
<img src="https://divine-star-software.github.io/DigitalAssets/images/logo-small.png">
</p>

---

A library for different types of RNG such as perlin noise and seeded RNG. 

```ts
import { PerlinNoise3d } from "divine-rng";
import { IndexedRNG } from "divine-rng";

const perlin = new PerlinNoise3d();
perlin.noiseSeed(2934782394782372);
const indexRNG = new IndexedRNG(2934782394782372);
const v = perlin.get(0,0,1);
const v2 = indexRNG.get(12);
```