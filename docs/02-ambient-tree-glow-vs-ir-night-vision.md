# 02 — Ambient Christmas Tree Glow (2500K) vs 850nm/940nm Infrared Night-Vision

Home security cameras record night scenes in two optically distinct modes depending on ambient room brightness:

## Mode A: Low-Light Color ("Starlight" / Night-Cam Sensor)

Modern CMOS security sensors stay in color mode when warm Christmas tree lights (`2,400K – 2,700K`) or fireplace mantel garlands provide `3–15 lux` of ambient illumination.

- **Key Light Direction**: The Christmas tree acts as a vertical softbox. Any person standing `0.8m` to the left of the tree receives warm amber key light on their right cheek, beard, and coat sleeve, while their opposite side falls into cool `4,500K–5,500K` room shadow.
- **Floor Contact Shadows**: Multi-bulb string lights cast a **soft-edged directional shadow** away from the tree plus a tight dark **contact occlusion crease** (`2–4 cm`) directly beneath boot soles.
- **OSD Timestamps**: Avoid pasting generic VCR overlays or hardcoded date stamps with mismatched fonts; clean uncropped camera exports match what parents save from modern home-cam phone apps.

## Mode B: Monochrome Near-Infrared (`850nm` / `940nm` IR LEDs)

When room lights are off (or when switching explicitly to [Infrared Night-Vision mode](https://catchsantainmyhouse.com/catch-santa-on-camera)), the camera retracts its IR-cut filter and illuminates the room with ring LEDs centered around the lens:

| Material in Room | Visible Daylight Color | Near-IR (`850nm`) Appearance | Why It Happens |
| :--- | :--- | :--- | :--- |
| **Dyed Red Velvet Coat** | Deep crimson red | **Bright silver-grey / pale white** | Organic red fabric dyes transmit near-IR wavelengths onto the reflective base fibers |
| **Faux Fur Trim & Beard** | Crisp white | **High-contrast white** | Synthetic fibers scatter coaxial IR LED light strongly back toward the lens |
| **Evergreen Pine Needles** | Dark forest green | **Medium-light grey** | Chlorophyll & PVC foliage reflect near-IR (the Wood effect) |
| **Distant Hallway Walls** | Warm beige / white | **Dark charcoal falloff** | Coaxial IR LED brightness drops by inverse-square law ($1/d^2$) with distance from camera |
| **Glass Eyeglasses / Ornaments** | Clear / colored | **Pinpoint centre specular glint** | Coaxial ring LEDs reflect straight back along the optical axis |
