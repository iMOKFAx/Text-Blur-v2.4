# Text Blur v2.4

**After Effects Script — by Mohamed Mostafa**

Text Blur creates smooth blur reveals for Adobe After Effects, word by word or letter by letter, in one click.

It includes 12 ready-made animation styles, editable Motion and Look controls, Flow-style speed curves, and optional after-motion effects. No keyframes are required: move or trim the text layer and the animation follows automatically.

## Features

- 12 ready-made styles
- Animate by words or letters
- Five reveal directions
- Adjustable delay, duration, stagger, blur, distance, scale, and tracking
- Cubic-bezier speed curves
- Side fade edges
- Pop-last-word option
- After-motion effects:
  - Slow Zoom
  - Slow Zoom Out
  - Drift
  - Tracking Breathe
  - Float
- Expression-driven workflow with no keyframes
- Editable anytime from After Effects Effect Controls
- Supports Arabic / RTL text workflows

## Installation

Text Blur is a single file:

`TextBlur.jsx`

### Install as a dockable panel

Copy `TextBlur.jsx` to the After Effects ScriptUI Panels folder.

**Windows**

`C:\Program Files\Adobe\Adobe After Effects <version>\Support Files\Scripts\ScriptUI Panels\`

**macOS**

`/Applications/Adobe After Effects <version>/Scripts/ScriptUI Panels/`

Restart After Effects, then open:

**Window → TextBlur.jsx**

You can dock the panel anywhere in the After Effects interface.

### Run without installing

You can also run the script directly from:

**File → Scripts → Run Script File…**

Then select `TextBlur.jsx`.

### Social links

If the social buttons do not open, enable:

**Preferences → Scripting & Expressions → Allow Scripts to Write Files and Access Network**

Text Blur itself works without this option. It is only required for opening the social links directly.

## How to Use

1. Select one or more text layers in the timeline.
2. Open the **Styles** tab and choose a preset.
3. Fine-tune the settings in **Motion** and **Look** if needed.
4. Click **Apply to selected text**.
5. Move the time indicator to the beginning of the layer and preview the animation.

Text Blur works on text layers only.

## Included Styles

- Soft Rise
- SaaS Slide
- Slide RTL
- Center Bloom
- Letter Mist
- Focus Pull
- Snap Pop
- Drop In
- Tracking In
- Flow In-Out
- Whisper
- Side Wipe

## Motion Controls

### Direction

Available directions:

- Up
- From Left
- From Right
- Center Out
- Down

### Animate By

Choose whether the animation runs by:

- Words
- Letters

### Delay

Controls how long the animation waits after the layer starts before the first word or letter appears.

### Duration

Controls how long each word or letter takes to fully appear.

### Stagger

Controls the time gap between one word or letter and the next.

### Speed Curve

Uses a cubic-bezier easing curve in the same format commonly used by Flow and CSS.

Example:

`0.16, 1, 0.3, 1`

### After Motion

Adds a subtle continuous motion that begins during the reveal.

Options:

- None
- Slow Zoom
- Slow Zoom Out
- Drift
- Tracking Breathe
- Float

### Motion Amount

Controls the strength of the selected after-motion effect.

## Look Controls

### Blur

Controls how blurry each word or letter starts. The blur always resolves to zero.

### Distance

Controls how far the text travels during the reveal.

### Start Scale

Controls the initial scale before the text settles into its final size.

### Start Tracking

Adds extra letter spacing at the start of the animation.

### Side Fade Width

Controls the width of the soft fade on each side of the line.

### Side Fade Edges

Softly fades the left and right edges so text can glide through a softer boundary.

### Pop Last Word

Adds a small scale hit to the final word or letter.

## Main Buttons

### Apply to selected text

Applies Text Blur to every selected text layer.

Applying Text Blur again replaces the previous Text Blur setup on that layer.

### Exit here

Creates a blur-and-fade exit beginning at the current time indicator.

To cancel the exit, set:

`TB Out At (s) = -1`

### Remove

Removes everything added by Text Blur without changing the original text.

## Editing After Applying

Text Blur does not create keyframes.

Instead, it creates controls whose names start with `TB`.

Select the text layer and press **F3** to open Effect Controls and edit the animation at any time.

Main controls include:

- TB Direction
- TB Delay (s)
- TB Duration (s)
- TB Stagger (s)
- TB Distance (px)
- TB Blur
- TB Start Scale (%)
- TB Start Tracking
- TB Curve X1 / Y1 / X2 / Y2
- TB After Motion
- TB After Motion Amount
- TB Out At (s)
- TB Side Fade (px)
- TB Pop Last

The script also creates the required Text Blur animators, mask, and exit blur effect. These are driven by the controls above.

## Tips

- Use Motion Blur for smoother sideways movement.
- For Arabic text, use **Slide RTL** or **From Right**.
- For Arabic, animating by **Words** helps keep connected letters intact.
- Try **Center Bloom** or **Focus Pull** for short headlines.
- Use **Snap Pop** for fast, music-driven edits.
- A colored final word works well with **Pop Last Word**.

## Troubleshooting

### No motion?

Move the time indicator to the beginning of the text layer and preview again. The reveal starts where the layer starts.

### “Select TEXT layers”?

Select a text layer in the timeline before clicking Apply.

### Links do not open?

Enable:

**Preferences → Scripting & Expressions → Allow Scripts to Write Files and Access Network**

### Panel too tall?

Resize the panel or dock it in a wider area.

### Want a clean start?

Click **Remove**, then apply Text Blur again.

### Changed the text?

You do not need to reapply the script. The timing updates automatically.

## Author

**Mohamed Mostafa**

LinkedIn: https://www.linkedin.com/in/mohamed-m-omaar/  
Instagram: https://www.instagram.com/mohamed.mostafa.m.omar/  
Facebook: https://www.facebook.com/iMOKFA/

---

Text Blur v2.4 · After Effects Script
