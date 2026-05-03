## Asking an agent to enrich a draft prompt

read the below prompt and template. Your job is to absorb the prompt and fill in the sections of the template. Your output is the filled template give the contents in prompt.

`---prompt starts---`

\{prompts\}

`---prompt ends---`

`---template starts---`

[MAIN SUBJECT]:
A detailed depiction of [subject], including key features such as [appearance, clothing, materials, colors, expression].

[STYLE / MEDIUM]:
In the style of [art style, e.g., photorealistic, anime, oil painting, cinematic, 3D render, pixel art].

[COMPOSITION / FRAMING]:
[Camera angle, shot type, framing — e.g., close-up portrait, wide-angle shot, centered composition, dynamic perspective].

[ENVIRONMENT / BACKGROUND]:
Set in [location/scene], featuring [background details, weather, time of day, atmosphere].

[LIGHTING]:
Lighting is [type — e.g., soft natural light, dramatic shadows, neon glow, golden hour, studio lighting].

[COLOR PALETTE]:
Dominant colors include [colors], creating a [mood — e.g., warm, moody, vibrant, desaturated] tone.

[MOOD / EMOTION]:
The overall feeling is [emotion or vibe — e.g., peaceful, tense, futuristic, nostalgic].

[DETAIL LEVEL]:
Highly detailed with [textures, small elements, realism level, sharpness].

[EXTRA ELEMENTS]:
Include [props, secondary subjects, motion, effects like fog, particles, reflections].

[ASPECT RATIO / FORMAT]:
--ar [e.g., 1:1, 16:9, 9:16]

[QUALITY TAGS]:
Ultra high resolution, 8k, sharp focus, professional, masterpiece


`---template ends---`

your job is to update the template, not to generate image

## Bliss Daily Menu

Please format the following OCR extracted text into the template

`---OCR extract starts---`

`---OCR extract ends  ---`

`---template starts---`

[Typography & Content]
Text centered on the menu card. High readability, perfectly aligned grid layout, generous line spacing.
Top center features a small baby blue heart icon.

Below the heart, elegant script font reading exactly: "Bliss Daily Specials"

Below that, clean modern sans-serif font reading exactly: "{{Date}}"

(Optional Section Main)Below that, separated by spacing, reading exactly: "— Main —"

Below that: "• {{item1}}"

Below that: "• {{item2}}"

(Optional Section Healthy Main)Below that, separated by spacing, reading exactly: "— Healthy Main —"

Below that: "• {{item1}}"

Below that: "• {{item2}}"

(Optional Section Snacks)Below that, separated by spacing, reading exactly: "— Snacks —"

Below that: "• {{item1}}"

Below that: "• {{item2}}"

(Optional Section Dessert)Below that, separated by spacing, reading exactly: "— Dessert —"

Below that: "• {{item1}}"

Below that: "• {{item2}}"

`---template ends  ---`

### Post Prompt

[System/Style]
Minimalist premium food photography, true 90-degree overhead flat lay composition, ultra-clean geometric layout, perfectly symmetrical visual hierarchy. Shot on 100mm macro lens, photorealistic, 8k resolution. Atmosphere: Calm, healing, airy, "Bliss" premium lifestyle brand.

[Lighting & Environment]
Background: Seamless crisp white marble surface.
Lighting: Soft diffused natural morning sunlight originating strictly from the top-left corner at a 45-degree angle, casting gentle, elongated, soft baby blue (#89CFF0) shadow gradients toward the bottom-right. Subtle frosted glass texture overlaying the background negative space.

[Main Composition]
A perfectly centered, elegant rectangular menu card with rounded corners and matte paper texture. The menu card shares the exact 9:20 aspect ratio of the main image canvas and occupies exactly 75% of the total frame, leaving an even, symmetrical border of the marble background on all four sides.

[Food Styling]
Exactly one high-end dish cropped partially into the frame from the bottom-right corner, showing only the top-left quarter of a white ceramic plate. The dish displays hyper-detailed macro textures (glossy glaze, tender protein, smooth cream). Absolute zero clutter. High negative space.

[Typography & Content]
Text centered on the menu card. High readability, perfectly aligned grid layout, generous line spacing.
Top center features a small baby blue heart icon.

Below the heart, elegant script font reading exactly: "Bliss Daily Specials"

Below that, clean modern sans-serif font reading exactly: "{{Date}}"

(Optional Section Main)Below that, separated by spacing, reading exactly: "— Main —"

Below that: "• {{item1}}"

Below that: "• {{item2}}"

(Optional Section Healthy Main)Below that, separated by spacing, reading exactly: "— Healthy Main —"

Below that: "• {{item1}}"

Below that: "• {{item2}}"

(Optional Section Snacks)Below that, separated by spacing, reading exactly: "— Snacks —"

Below that: "• {{item1}}"

Below that: "• {{item2}}"

(Optional Section Dessert)Below that, separated by spacing, reading exactly: "— Dessert —"

Below that: "• {{item1}}"

Below that: "• {{item2}}"


[Negative Prompt]
Dark tones, red/yellow dominant colors, messy layout, multiple dishes, silverware, cups, clutter, blurry text, distorted typography, low resolution, human hands, harsh black shadows, depth of field blur, wood textures.

[Parameters]
--ar 9:20 --style raw --v 6.0
