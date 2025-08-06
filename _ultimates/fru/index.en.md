---
layout: default
title: Lv 100. FRU
nav_order: 6
has_children: true
has_toc: false
permalink: /ultimates/fru/
---

# Futures Rewritten (Ultimate)

Mana does the [new Lily Doll strat](https://jp.finalfantasyxiv.com/lodestone/character/34120564/blog/5500375/),
which is basically Lily Doll's original strat, but has P4 and P5 replaced with
Nukemaru's strats, which you'll see written as "P123リリドP45ぬけまる(アポカリ基準/扇前)".

### BiS Notes

- BiS will be a mix of gear from:
  - **i730**: M1-4S (AAC Light-heavyweight (Savage)).
  - **i730**: The Cloud of Darkness (Chaotic).
  - **i735**: Dungeon gear from *The Meso Terminal*.
- Use the highest grade potions available.

Looking towards the future:

- Futures Rewritten will not be outgeared until **i860** gear is available in
Patch 8.0.
- Relic weapons (when they arrive) will have their substats capped at **393**.

 <div id="gallery" class="gallery">
  <a href="https://akanabanana.github.io/FFXIVPF2/Assets/Images/cheatsheet/FRU_Mana_EN.png" data-mediabox="gallery-1" data-title="FRU Mana">
    <img style="max-width: 90%" src="https://akanabanana.github.io/FFXIVPF2/Assets/Images/cheatsheet/FRU_Mana_EN.png" alt="Image 1">
  </a>
</div>
   
(Full-size image
[English](https://akanabanana.github.io/FFXIVPF2/Assets/Images/cheatsheet/FRU_Mana_EN.png), [日本語](https://akanabanana.github.io/FFXIVPF2/Assets/Images/cheatsheet/FRU_Mana_JP.png))


   
---

## PoVs

Here are some clear PoVs that I've been collecting.

- [MT PoV (DRK)](https://youtu.be/RLlQPO0QOgk)
- [ST PoV (PLD)](https://youtu.be/R17LKD903i0)
- [H1 PoV (WHM)](https://youtu.be/0LpJ-1tLbhw)
- [H2 PoV (SCH)](https://youtu.be/r69DXp-O3_g)
- [D1 PoV (DRG)](https://youtu.be/U-ZtFdpiBQ8)
- [D2 PoV (NIN)](https://youtu.be/m6EVjNmyGUU)
- [D3 PoV (BRD)](https://youtu.be/vkUfqQi5qFo)
- [D4 PoV (PCT)](https://youtu.be/Lg_H3FXANDc)

---

## Markers

![]({{site.baseurl}}/images/ultimates/fru/markers.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"FRU",
  "MapID":1006,
  "A":{"X":100.0,"Y":0.0,"Z":90.0,"ID":0,"Active":true},
  "B":{"X":110.0,"Y":0.0,"Z":100.0,"ID":1,"Active":true},
  "C":{"X":100.0,"Y":0.0,"Z":110.0,"ID":2,"Active":true},
  "D":{"X":90.0,"Y":0.0,"Z":100.0,"ID":3,"Active":true},
  "One":{"X":107.071,"Y":0.0,"Z":92.929,"ID":5,"Active":true},
  "Two":{"X":107.071,"Y":0.0,"Z":107.071,"ID":6,"Active":true},
  "Three":{"X":92.929,"Y":0.0,"Z":107.071,"ID":7,"Active":true},
  "Four":{"X":92.929,"Y":0.0,"Z":92.929,"ID":4,"Active":true}
}
```

</details>

---

## Japanese

This is the **Apocalypse-relative** macro taken from [Lily Doll's Lodestone post](https://jp.finalfantasyxiv.com/lodestone/character/34120564/blog/5500375/).

{% include_relative macros/fru.jp.md %}

---

## Frequently Asked Questions

<details markdown=block>
<summary>
  <b>[Damage Down]</b> How strong is the damage down debuff in this fight?
</summary>
<table>
  <tr>
    <td>
      <p>There are actually <em>two</em> different Damage Down debuffs in this 
      encounter, both of which lowers a player's damage by <b>90%</b>.</p>
      <ul>
        <li><em>Damage Down</em> comes from getting hit by avoidable attacks.</li>
        <li><em>Mark of Mortality</em> comes from resolving stacks with less 
        than the required number of players.</li>
      </ul>
      <p>These damage downs also come from two separate debuffs, so <em>they
      stack</em> together for a combined <b>99% damage down!</b></p>
    </td>
    <td style="text-align:center">
      <img src="{{site.baseurl}}/images/ultimates/fru/01/damage_down.png">
      <img src="{{site.baseurl}}/images/ultimates/fru/01/mark_of_mortality.png">
    </td>
  </tr>
</table>
</details>

<script data-goatcounter="https://xivjpraids.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>
