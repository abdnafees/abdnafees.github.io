---
published: false
---

# Images

Put post images in `assets/images/posts/<post-date>/`, e.g.
`assets/images/posts/2026-11-02/hall-road-kit.jpg`.

Keep them under ~300 KB (resize to 1600px wide, JPEG quality ~80).

In a post, either:

    ![ESP32 on a breadboard](/assets/images/posts/2026-11-02/esp32.jpg)

or, with a caption:

    {% include figure.html src="/assets/images/posts/2026-11-02/esp32.jpg" alt="ESP32 on a breadboard" caption="First blink." %}

To set the image shown when the post is shared on X/WhatsApp/LinkedIn, add to the post's front matter:

    image: /assets/images/posts/2026-11-02/esp32.jpg
