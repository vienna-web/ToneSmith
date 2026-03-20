
# ToneSmith Deck

## A Professional DIY MIDI Creative Control Surface

ToneSmith Deck is a high-input, USB-MIDI control surface designed to provide fast, tactile access to creative software controls.
Built around an Arduino Pro Micro and analog multiplexing, ToneSmith Deck replaces repetitive mouse work with precise physical interaction — accelerating editing, sound design, and parameter control workflows.

# Key Features
* 48 total hardware inputs,32 precision 10k potentiometers,16 programmable buttons,USB plug-and-play MIDI output,Navigation controls,Undo / Redo functionality,Expandable firmware,Fully customizable labels and control layout
# Technical Overview
i will be ussing this parts for my project 
 Arduino Pro Micro (USB HID enabled)
 3× CD74HC4067 multiplexers (48 total inputs)
 Control Surface Arduino library
 USB MIDI protocol
 Custom PCB (Gerber files included)
 3D printed enclosure
toonsmith will connect via USB and is recognized by the system as a just like a normal MIDI controller

#  Hardware Components & Cost Breakdown
| Product | Quantity | Source | Price(INR) | Price($) | Link |
| :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |

| Arduino Pro Micro  | 1| Typeractive |  $12    | 2 | [here](https://www.aliexpress.com/item/1005010771143760.html?spm=a2g0o.productlist.main.30.6a1eSAm0SAm0TW&utparam-url=scene%3Asearch%7Cquery_from%3Apc_back_same_best%7Cx_object_id%3A1005010771143760%7C_p_origin_prod%3A&algo_pvid=e2dcd4ff-e80c-473e-a5c0-635b0399cc18&algo_exp_id=e2dcd4ff-e80c-473e-a5c0-635b0399cc18&pdp_ext_f=%7B%22order%22%3A%227%22%2C%22spu_best_type%22%3A%22price%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%2116.66%2112.33%21%21%21114.10%2184.43%21%40211b80e117740289311126271ed214%2112000053458956135%21sea%21MA%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ac85f81ee%3Bm03_new_user%3A-29895) |
| CD74HC4067 Multiplexer |3| Typeractive | - |  $15  | [here]( https://www.aliexpress.com/item/1005010279922760.html?spm=a2g0o.productlist.main.17.5da5Aa36Aa36Ae&algo_pvid=be661794-2b75-466f-836e-2193ecae405f&algo_exp_id=be661794-2b75-466f-836e-2193ecae405f-22&pdp_ext_f=%7B%22order%22%3A%22-1%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%215.60%215.60%21%21%2138.38%2138) |
|| 10k RV09 Potentiometers  | 32  | Typeractive | - |$48 | [here]( https://www.aliexpress.com/item/1005006089154415.html?spm=a2g0o.productlist.main.3.386dtmantmanjl&algo_pvid=b3dd4525-04eb-4368-8e7c-60651057bcc1&algo_exp_id=b3dd4525-04eb-4368-8e7c-60651057bcc1-2&pdp_ext_f=%7B%22order%22%3A%22908%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%2110.96%212.48%21%21%2175.08%2116.99%21%402103963717740291954505117e3b15%2112000035681445210%21sea%21MA%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ac85f81ee%3Bm03_new_user%3A-29895%3BpisId%3A5000000197841489&curPageLogUid=5WUSotBdxpf0&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006089154415%7C_p_origin_prod%3A) |
  Tactile/Silicone Buttons | 16  | Typeractive | - |  $20  | [here](     https://www.aliexpress.com/item/4000681606445.html?spm=a2g0o.productlist.main.7.2fd2RYmURYmU6I&algo_pvid=137d31c7-1da1-485f-8b9f-c160e38672ac&algo_exp_id=137d31c7-1da1-485f-8b9f-c160e38672ac-6&pdp_ext_f=%7B%22order%22%3A%2271%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%212.46%210.99%21%21%212.46%210.99%21%40211b680e17740292501491752e1e56%2110000005991506993%21sea%21MA%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ac85f81ee%3Bm03_new_user%3A-29895%3BpisId%3A5000000197841472&curPageLogUid=iuy6El7p7vNS&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A4000681606445%7C_p_origin_prod%3A) |
| Custom PCB (JLCPCB)| 1 | Typeractive | - |$48 | [here]() |
 3D Printed Case (PLA)    | 1 | Typeractive | 1 |  $15  | [here]() |
| Knobs & Button Caps | 48 | Typeractive | 48  | $20 | [here]() |
 Wiring, headers, screws  | - | Typeractive | - |  $15  | [here]() |
|Sticker printing    |- | Typeractive | - | 20  | [here]() |

### Total Estimated Build Cost:
**$250**

## PCB

(![alt text](![image](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI0MzQ0LCJwdXIiOiJibG9iX2lkIn19--1521856345e9dc9b6d08d8823bb801f6297d3c73/image.png))) | 
