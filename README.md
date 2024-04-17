# Kai Simple, an easy-to-build diodeless, wireless split keyboard

Kai Simple is a cradio (or some call it Sweep) variation that fits author's hand best.
Author's first KB design: https://github.com/kaihchang/Ascend_splay_split_keyboard

ZMK config: https://github.com/kaihchang/zmk-config-kai-simple
MCUs face up for englmaxi's ZMK on-board LED widget. Front-facing built-in LEDs are utilized to present battery and connection status. I used n!n replicas, they only have 1 led each, so sadly no layer change indications.

<table>
  <tr>
    <td>![PXL_20240416_033003648](https://github.com/kaihchang/Kai_Simple_split_keyboard/assets/43580584/edc0f60a-1226-40ee-81c9-d224d18218f4)</td>
  </tr>
  <tr>
    <td>![PXL_20240414_013830746](https://github.com/kaihchang/Kai_Simple_split_keyboard/assets/43580584/c0858064-9b8c-4e9d-b475-5aa7d8976fc1)</td>
    <td>![螢幕擷取畫面 2024-04-08 094835](https://github.com/kaihchang/Kai_Simple_split_keyboard/assets/43580584/f0653513-c4e7-4a71-977d-63f0e90abb41)</td>
  </tr>
</table>

I've been using my last Ascend KB for a month, while it is comfortable, MX switches are still relatively big and wide. Maybe it's bc I have small hands or was used to Sweep before it, I started missing Chocs, so that's why there's this Simple.
Originally I designed Simple with the shortest (12mm) EC11 knobs I can find, but didn't like the look and figured that I don't really need knobs, and without them I can also skip diodes and make the build cleaner, so I went for 1 pin for each switch.
I'll probably stick with ZMK but just in case something went wrong with the power circuits (unlikely), I left a pin for TRRS connectors.
