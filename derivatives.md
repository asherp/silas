## Derivatives

$$ \frac{f(x + dx) - f(x)}{dx} = \frac{df}{dx} = f\prime(x) $$

$$ \frac{d(f(x) + g(x))}{dx} = \frac{f(x + dx) + g(x + dx) - f(x) -g(x)}{dx} = \frac{f(x + dx) - f(x)}{dx} + \frac{g(x + dx) - g(x)}{dx} = \frac{df}{dx} + \frac{dg}{dx} $$

$$ \frac{d(f(x) + g(x))}{dx} = \frac{df}{dx} + \frac{dg}{dx} $$

$$ f(x + dx) = f(x) + df $$

$$ \frac{d(f(x)g(x))}{dx} = \frac{(f(x) + df)(g(x) + dg) - f(x)g(x)}{dx} = \frac{f(x)g(x) + f(x)dg + dfg(x) + dfdg - f(x)g(x)}{dx} = f(x)\frac{dg}{dx} + \frac{df}{dx}g(x) + \frac{dfdg}{dx} $$

$$ \frac{dfdg}{dx} \approx 0 $$

$$ \frac{d(f(x)g(x))}{dx} = f(x)\frac{dg}{dx} + \frac{df}{dx}g(x) $$

$$ (f(x)g(x))\prime = f(x)g\prime(x) + f\prime(x)g(x) $$

$$ \frac{f(x + \Delta x) - f(x)}{\Delta x} = \frac{df}{dx} $$

$$ \Delta x \approx 0 $$

$$ \frac{d(f(g(x)))}{dx} = \frac{f(g(x + dx)) - f(g(x))}{dx} = \frac{f(g(x) + dg) - f(g(x))}{dx} $$

$$ \frac{f(g(x) + dg) - f(g(x))}{dg} = \frac{df}{dx}(g(x)) $$

$$ \frac{f(g(x) + dg) - f(g(x))}{dg}\frac{dg}{dx} $$

$$ = \frac{d(f(g(x)))}{dx} = \frac{df}{dx}(g(x))\frac{dg}{dx} $$

$$ (f(g(x)))\prime = f\prime(g(x))g\prime(x)$$
