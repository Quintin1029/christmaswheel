# 🎅 Saint Nick’s Christmas Wheel 🎄

A festive, interactive spin-the-wheel game for Christmas gift exchanges and party chaos.

This version runs **entirely in your browser** — no Python, no server required.

---

## ▶️ How to Open the Wheel
1. Double-click `index.html`
2. It will open in **Chrome** (or another modern browser, but only tested with chrome)
3. Click the 🎁 in the center to spin
> Note: if the page is refreshed, the wheel will completely reset, so be careful!

That’s it!

### Sound controls
- Click **🔊 / 🔇 Sound on/off** at the bottom to mute or unmute
- Make sure browsers have sound enabled.

---

## 🎄 Customizing the Wheel

To change actions or people:

1. Open `index.html` in a text editor
2. Find the section near the top that looks like this:

```html
<script type="application/json" id="wheel-config">
{
  "actions": [
    "Open any gift 🎁",
    "Swap gifts with ____ and ____"
  ],
  "people": [
    "Quintin",
    "Erin",
    "Paddy"
  ]
}
</script>
```

3. Edit actions to add/remove items from the wheel.
    - Any action containing `____` will be replaced with a **random person**
    - Actions can have **multiple `____`**
    - Each `____` in the same action will be a **different person** (when possible)

4. Edit people to add/remove people.
5. Make sure the script is valid JSON or it will not properly load.
6. If you like, you can also change the title or other text by editing `index.html`.