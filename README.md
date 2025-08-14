
# Indian Flag Hoisting Animation

This project is a pure HTML & CSS animation that simulates the **hoisting of the Indian national flag**, followed by a **waving effect** and a **rotating Ashoka Chakra**.

## Features

* **Flag hoist animation**: The flag smoothly rises up the pole.
* **Waving tricolor**: Realistic waving effect using CSS keyframes.
* **Rotating Ashoka Chakra**: 24-spoke wheel rotates continuously after hoisting.
* **Pure HTML & CSS**: No JavaScript required.
* **Responsive design**: Scales to fit different screen sizes.

## How It Works

1. **Flag Hoisting**: The `.flag` element moves upward using CSS `transform` and `@keyframes hoist`.
2. **Waving Effect**: Once hoisted, the tricolor stripes use `@keyframes wave` with `background-position` shifting to simulate motion.
3. **Ashoka Chakra Rotation**: The `.chakra` rotates with `@keyframes spinChakra`, positioned in the white stripe.
4. **Timing**: The wave and rotation start after the hoisting animation completes.

## File Structure

```
index.html   # Main file containing HTML and CSS
```

## How to Run

1. Download or copy the `index.html` file.
2. Open it in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Watch the flag hoist and wave proudly.

## Customization

* **Animation Speed**: Adjust the duration in the `animation` properties.
* **Flag Size**: Change the `.flag` width and height.
* **Chakra Size**: Modify the `.chakra` dimensions.

## License

This project is free to use for educational and patriotic purposes.

---

🇮🇳 **Happy Independence Day!** Jai Hind!
