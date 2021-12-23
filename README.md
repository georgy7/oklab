Go port of
[reference implementation](https://bottosson.github.io/posts/oklab/#converting-from-linear-srgb-to-oklab)
converting linear sRGB to Oklab color space and vice versa.
It is double-precision because of `math.Cbrt`.

Please note that most image formats, including PNG and BMP,
store non-linear gamma-corrected colors.
