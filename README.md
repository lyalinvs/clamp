Взял отсюда
https://css-tricks.com/linearly-scale-font-size-with-css-clamp-based-on-the-viewport/#for-those-who-dont-mind-that-edge-case

clamp(fontMinpx, calc(fontMinpx + (fontMax - fontMin) * ((100vw - widthMinpx) / (widthMax - widthMin))), fontMaxpx);

