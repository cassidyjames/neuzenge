[![Validate](https://github.com/cassidyjames/neuzenge/actions/workflows/validate.yml/badge.svg)](https://github.com/cassidyjames/neuzenge/actions/workflows/validate.yml)

# Neuzenge

Lightweight, tactile theme for Home Assistant

![Light](docs/light.png) | ![Dark](docs/dark.png)
------------------------ | -----------------------

I was tired of over-complicated third-party themes, but felt like the stock Home Assistant theme could be just a little bit nicer/more modern. So, I made Neuzenge! It's designed to be fast and constrained while making Home Assistant feel a little more at home alongside modern UIs like Liquid Glass and Material You/Material Expressive.

Neuzenge is _mostly_ just the stock Home Assistant theme, with only a few targeted overrides to borders and shadows. The result is a fresh look where tiles and badges become smooth, elevated pills.

## Install

To add to Home Assistant, I recommend using Home Assistant Community Store (HACS).

1. Open HACS in Home Assistant
2. Select **︙ Overflow menu** → **Custom repositories**
3. Paste `https://github.com/cassidyjames/neuzenge.git` in the Repository, and select **Theme** for the type, then hit **Add**
4. Search for `neuzenge` in HACS
5. Select the **Neuzenge** theme, hit the **Download** button, and confirm by hitting **Download** again

### User theme

To set Neuzenge as your personal theme across devices:

1. Open your user menu from the sidebar
2. Under **User preferences** → **Theme**, select **Neuzenge**

### Default theme

To set Neuzenge as the default theme for all users:

1. Navigate to **Settings** → **Developer tools**
2. Select the **Actions** tab
3. Search for and select the **Set theme** (`frontend.set_theme`) action
4. Check the **Theme** option, and select Neuzenge under the **Theme** entry
5. Optionally (to override previous setting), check **Dark theme override** and select **No theme** to blank out the dark theme override
6. Hit **Perform action**
