# M497B · Summing

Ward-Beck Systems M497B, 1983|16. Wiki page: [M497B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M497B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 36 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 4 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 194 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 10 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 31 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [1983 - M497B - P003 - 1-1.jpg](MANUALS/1983%20-%20M497B%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | dB +/-0.5 dB nominal +2, dB provided. trim range |
| **Frequency response** | +0/-1 dB from Hz kHz (tailored frequency response) dB below dBu nominal output level (20 Hz 20 kHz) = |
| **Noise** |  |
| &nbsp;&nbsp;Harmonic distortion | Less than 0.259% THD, from Hz 20 kHz +27 dBm output less _ Less than 0.1% at kHz at +27 dBm output |
| **Source impedances** |  |
| &nbsp;&nbsp;Summing | External Oo0 ohms, balanced 600 ohms ma imum, balanced |
| **Input impedances** |  |
| &nbsp;&nbsp;Summing | External Less than ohms _ 30,000 ohms |
| &nbsp;&nbsp;Input level | External dBm nominal +16 dBm maximum. |
| **Output impedances** |  |
| &nbsp;&nbsp;Program | Mono: 150 ohms; balanced 36,000 ohms, balanced |
| **Load impedances** |  |
| &nbsp;&nbsp;Program | Mono: 600 ohms, balanced Summing, less than ohms, balanced |

## Circuit description

From [1983 - M497B - Dual Master Module (2).pdf](MANUALS/1983%20-%20M497B%20-%20Dual%20Master%20Module%20(2).pdf) pages 5-7 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M497 B.. cc om mo dates two s.. pa..a te signal chan n.. l s. I t is d.. sign..d to ee e tve t h.. mixed feeds from I h.. I.. ft and.. i g h t mix.... buses o f a conso l... T h.. two sl g n.. l s...... independently processed and.. mp llfi e d 10 stan da.. d line I e v ete • The outputs. oft h e M497B supply the main p rog..a m outputs oft h.. consoles y stem. Both channel sop....a te ina s imlla.. mann e... Th.. following d e sc.. ipt ion.... r.... s specifically to th.. LEFT c h.. nn.. l.

The signal originating from t h.... &quot;1.... '1.. 1 m i&quot;i n g n etwo..k en t.... s t h.. module a t pins l / A and i s applied tot h.. summing Cu r-r-e n t nod.. s o f Ul.. ndU2.

U l through U3, with t hei.. assocla t.. d components, prov ld.. a n.. ctiv ely bal.. nc e din put as w.. 11.. 5.. b al.. oc ee output. T h.. output ec....... t.. s.. t.. nomln.. 1 l eve 1 of 0 dGu.. nd.. pp......s a t pins 6/F.

A b.. i e e e.. d INSC RT point is provid.. d b.. t ween pins 6/F and 8J, p.... mitt ing t h.. ins.... tion of an.. &quot; t.... nal.. qu.. lize.., filt.... 0.. co m_ p ~s s o&quot;,.. i t h.... using an M499 in s.. rt switch.... orb y d lr..ct w i.. lng.

L.. v.. 1 Adjustment

From the INSERT point, the $I g n ali s.... turned tot h e module a t pins 8 /J and f.. d tot h.. a-10ge output amp ll fie.. via ana tt.. nu ato&quot; n.. two.. k. R4 2 I s a level t.. im potentlomet e.. p.. rmitting adj u s tm.. n t oft h e module output l ev.. 1 from +2 to +10 dBu with r.. f....enc e tot h e nominal l.. v.. 1 of +8 dBu. A small hoi.. int h.. module front pane 1 allows aCcesS tot h e I.. i m control.

The a_I09C output.. mpllf i.... op er.. t.. s with again of 39 dB. It r eco v....,. the loss oft h.. input netwo..k and p..o vl d es add i t i o na l gain to produce a nom in.. 1 lin.. level of +8 dBu Into 600 ohms a t the output of I he module.

A 150 ohm..es is t l v e dlv1ding network, having a loss of 2 dB (wh.. n

operated into a 600 ohm load), is i n s.. rt.. d bet we l!(&gt; t h.. a _109C and

t h.. t h..ee mod ul.. outputs a t pins 12/N, 13/ Pan d 14/R. T h.. amplifier outputs...... designed to no..mally op...... te into a b.. idg ing load (5K

ohms). Th.. amplfi erIs capable of delivering ama &quot;i mum output I..v e l

o f +27 dBm into 600 ohms a tan yon.. of its outputs (not all loaded s i multan..ou sly).

**&quot;&quot;. 9 78 DUAL &quot;&quot;AST ER MODULE**

RIGHT Ch. n n e l. n d MOHO OUl ou l

Th.,.Ight channel o f I I\e 104.9 78 op.,.. tes in • m. n n er s l ml la &quot; 10 Ihe left ch.nnel. s de s.c;rib ed e eev •.

For the &quot;&quot;ONO ou tp u l, bolh d' anne ls..... combined and apoea,. et pins 1 1/ &quot;&quot;. The signal leva loft his OUlpu l is such that,...l\en connected 10 Ihe summing inp u l o f a second &quot;&quot;.978, It... ill produce a n ou toU I o f +8 dBu,... il h the l. ft 0,.,.i g h l c h&quot;nn aloft h eli,.SI unit ope,.al ing &quot; I +8 dB u (Re 600 oh ms).

Po.....,.. Supp l... Dec oup l ln g

An.. cti v.. po&quot;,.,.. supply dec o up lln g n el...o,..k con si Sl l n g o f 01 Ihroug h 06 provides i sol al'o'&quot; bet &quot;, e.... Ih e module and the +/ _2! volts u p ply,.... 11'. transistors OJ and 06 monllor Ih e supply current. In the event of e &gt;&lt;ce s slve power ' u p ply demands, such a s from component failure 01&quot; amplifier ov erdri v.., the current flow, n g through 01 and 04 will b e limited.

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaFo4RklSRFBab0k/view?resourcekey=0-TZJpNdH4IrE9Lv_8HeFEgw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaFo4RklSRFBab0k&resourcekey=0-TZJpNdH4IrE9Lv_8HeFEgw" width="240" alt="1983 - M497B - 497-04-005 - DUAL MASTER MODULE.jpg"></a><br><sub>1983|16 · 497-04-005 - DUAL MASTER MODULE · <a href="MECHANICAL/1983%20-%20M497B%20-%20497-04-005%20-%20DUAL%20MASTER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTjlweThZLVlLc00/view?resourcekey=0-x8uqZ6Uo9F-lEjoCWvxxPQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTjlweThZLVlLc00&resourcekey=0-x8uqZ6Uo9F-lEjoCWvxxPQ" width="240" alt="1983 - M497B - 491-02-002 - ARS FROHT AANEL LEVEL CONTROLS.jpg"></a><br><sub>1983|16 · 491-02-002 - ARS FROHT AANEL LEVEL CONTROLS · <a href="SCHEMATICS/1983%20-%20M497B%20-%20491-02-002%20-%20ARS%20FROHT%20AANEL%20LEVEL%20CONTROLS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWkVnZ3VPZVNSZ0U/view?resourcekey=0-fx7TAFHhRNs38W_DEc1qow" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWkVnZ3VPZVNSZ0U&resourcekey=0-fx7TAFHhRNs38W_DEc1qow" width="240" alt="1983 - M497B - 497-01-003 - OHMS LEFT LEVEL INSERT.jpg"></a><br><sub>1983|16 · 497-01-003 - OHMS LEFT LEVEL INSERT · <a href="SCHEMATICS/1983%20-%20M497B%20-%20497-01-003%20-%20OHMS%20LEFT%20LEVEL%20INSERT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWmVWUkhqZVBJVTg/view?resourcekey=0-f8O8P5OnMwZjmfaWNqPLSQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWmVWUkhqZVBJVTg&resourcekey=0-f8O8P5OnMwZjmfaWNqPLSQ" width="240" alt="1983 - M497B - 497-01-003 - OUU ONMS.jpg"></a><br><sub>1983|16 · 497-01-003 - OUU ONMS · <a href="SCHEMATICS/1983%20-%20M497B%20-%20497-01-003%20-%20OUU%20ONMS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKalQ3TTktMWdIeGc/view?resourcekey=0-sEi_XIU50w1cALXGRLqhBA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKalQ3TTktMWdIeGc&resourcekey=0-sEi_XIU50w1cALXGRLqhBA" width="240" alt="1983 - M497B - 497-02-002 - CRI TIP.jpg"></a><br><sub>1983|16 · 497-02-002 - CRI TIP · <a href="SCHEMATICS/1983%20-%20M497B%20-%20497-02-002%20-%20CRI%20TIP%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeUYtTmpCdUhwc00/view?resourcekey=0-yqnF0UbpTf3sjRknptYcvA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeUYtTmpCdUhwc00&resourcekey=0-yqnF0UbpTf3sjRknptYcvA" width="240" alt="1983 - M497B - 497-06-005 - DUAL MASTER MODULE.jpg"></a><br><sub>1983|16 · 497-06-005 - DUAL MASTER MODULE · <a href="SCHEMATICS/1983%20-%20M497B%20-%20497-06-005%20-%20DUAL%20MASTER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUlNfZGZoRWtsNm8/view?resourcekey=0-ydOvPLwO6ouo715Ni5KyWQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUlNfZGZoRWtsNm8&resourcekey=0-ydOvPLwO6ouo715Ni5KyWQ" width="240" alt="1983 - M497B - 497-06-005 - TIPSOD WIPZST.jpg"></a><br><sub>1983|16 · 497-06-005 - TIPSOD WIPZST · <a href="SCHEMATICS/1983%20-%20M497B%20-%20497-06-005%20-%20TIPSOD%20WIPZST%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOURQbURtdkpXekk/view?resourcekey=0--3FgDo-BiCoFLT5N5iSwhQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOURQbURtdkpXekk&resourcekey=0--3FgDo-BiCoFLT5N5iSwhQ" width="240" alt="1983 - M497B - 8-109-02-004 - NOMINAL VALUE (2).jpg"></a><br><sub>1983|16 · 8-109-02-004 - NOMINAL VALUE (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWkxSZ0k5akpna28/view?resourcekey=0-pX-NFSFrOykzjQ-UKarXNw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWkxSZ0k5akpna28&resourcekey=0-pX-NFSFrOykzjQ-UKarXNw" width="240" alt="1983 - M497B - 8-109-02-004 - NOMINAL VALUE.jpg"></a><br><sub>1983|16 · 8-109-02-004 - NOMINAL VALUE</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVlhheEZoMmswZWs/view?resourcekey=0-_WKNV23e-aodqfdDmojWHg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVlhheEZoMmswZWs&resourcekey=0-_WKNV23e-aodqfdDmojWHg" width="240" alt="1983 - M497B - 8-109-06-004 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1983|16 · 8-109-06-004 - BOOSTER AMPLIFIER</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTHVoU2pGS1ZnMHM/view?resourcekey=0-HOXlcrRcauG4IXFo4R0tNw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTHVoU2pGS1ZnMHM&resourcekey=0-HOXlcrRcauG4IXFo4R0tNw" width="240" alt="1983 - M497B - 8-109-06-004.jpg"></a><br><sub>1983|16 · 8-109-06-004</sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M497B - RTO-144 Connections.pdf`

## RTO-144 pinout

21 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | LEFT SUM IN | in | A1 + | high |
| 2 | RIGHT SUM IN | in | A2 + | high |
| 4 | LEFT LINE IN | in | B1 + | high |
| 5 | RIGHT LINE IN | in | B2 + | high |
| 12 | OUT LEFT | out | A3 + | high |
| 14 | VU OUT LEFT | out | B3 + | high |
| 15 | OUT RIGHT | out | A4 + | high |
| 17 | VU OUT RIGHT | out | B4 + | high |
| 19 | -25 V | power |  | high |
| 20 | COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| A | LEFT SUM IN | in | A1 - | high |
| B | RIGHT SUM IN | in | A2 - | high |
| D | LEFT LINE IN | in | B1 - | high |
| E | RIGHT LINE IN | in | B2 - | high |
| N | OUT LEFT | out | A3 - | high |
| R | VU OUT LEFT | out | B3 - | high |
| S | OUT RIGHT | out | A4 - | high |
| U | VU OUT RIGHT | out | B4 - | high |

**Straps:** Insert LEFT +: JMP.8.6 · Insert LEFT -: JMP.F.J · Insert Right +: JMP.7.9 · Insert Right -: JMP.H.K

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKXzlHNGk5MDFHc00/view?resourcekey=0-DSFq8cALyUR5qgMDwdkmKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKXzlHNGk5MDFHc00&resourcekey=0-DSFq8cALyUR5qgMDwdkmKg" width="240" alt="1983 - M497B - Dual Master Module (2).pdf"></a><br><sub>1983|16 · Dual Master Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLUFKNVQtWHV4NUE/view?resourcekey=0-5-DY-4h73wsOWjgmjP-RJA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLUFKNVQtWHV4NUE&resourcekey=0-5-DY-4h73wsOWjgmjP-RJA" width="240" alt="1983 - M497B - Dual Master Module.pdf"></a><br><sub>1983|16 · Dual Master Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOUhVRG1UUjhMQUU/view?resourcekey=0-SVX6vmpHJHOlXGCLfqX9wA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOUhVRG1UUjhMQUU&resourcekey=0-SVX6vmpHJHOlXGCLfqX9wA" width="240" alt="1983 - M497B - P001 - Title Page.jpg"></a><br><sub>1983|16 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUnZkckxybHk5RE0/view?resourcekey=0-KlxBVdB8dRs28_hiWWZwfw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUnZkckxybHk5RE0&resourcekey=0-KlxBVdB8dRs28_hiWWZwfw" width="240" alt="1983 - M497B - P002.jpg"></a><br><sub>1983|16 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXFVaTJEYUpzVXc/view?resourcekey=0-GfwKBlcrKeeb1T3EzS2FZQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXFVaTJEYUpzVXc&resourcekey=0-GfwKBlcrKeeb1T3EzS2FZQ" width="240" alt="1983 - M497B - P003 - 1-1.jpg"></a><br><sub>1983|16 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRUJQa1NNVXlJb00/view?resourcekey=0-SKf2VjxT1R8nCxj0Jy94iQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRUJQa1NNVXlJb00&resourcekey=0-SKf2VjxT1R8nCxj0Jy94iQ" width="240" alt="1983 - M497B - P004 - 1-2.jpg"></a><br><sub>1983|16 · P004 - 1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMjlXMVR3dkdodms/view?resourcekey=0-mxbdsj8pqRaI1zCJ0nnqgQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMjlXMVR3dkdodms&resourcekey=0-mxbdsj8pqRaI1zCJ0nnqgQ" width="240" alt="1983 - M497B - P005 - 2-1.jpg"></a><br><sub>1983|16 · P005 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSW80THQyb3pxRlE/view?resourcekey=0-W6wgapnAfkpmNqwXtyyaSg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSW80THQyb3pxRlE&resourcekey=0-W6wgapnAfkpmNqwXtyyaSg" width="240" alt="1983 - M497B - P006 - 2-2.jpg"></a><br><sub>1983|16 · P006 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQklVNTkxTk1ZUGs/view?resourcekey=0-4lPDcBiN7cSjlfGUsjAvpA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQklVNTkxTk1ZUGs&resourcekey=0-4lPDcBiN7cSjlfGUsjAvpA" width="240" alt="1983 - M497B - P007 - 3-1.jpg"></a><br><sub>1983|16 · P007 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcWtFLWMtQzZ4VlE/view?resourcekey=0-gsUX6cy8ddnoS2-83EquFQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcWtFLWMtQzZ4VlE&resourcekey=0-gsUX6cy8ddnoS2-83EquFQ" width="240" alt="1983 - M497B - P008 - 3-2.jpg"></a><br><sub>1983|16 · P008 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdjZSUi1MQnRwNUE/view?resourcekey=0-IVMh_vcZJ67wsYRzRLqNUg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdjZSUi1MQnRwNUE&resourcekey=0-IVMh_vcZJ67wsYRzRLqNUg" width="240" alt="1983 - M497B - P009 - 3-3.jpg"></a><br><sub>1983|16 · P009 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVWtEMFBTaUhqdjQ/view?resourcekey=0-ezTGeUjTs-8iE1BUCn7JUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVWtEMFBTaUhqdjQ&resourcekey=0-ezTGeUjTs-8iE1BUCn7JUw" width="240" alt="1983 - M497B - P010 - 3-4.jpg"></a><br><sub>1983|16 · P010 - 3-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNmZ1UDFYMXl4alU/view?resourcekey=0-uEbQvVcPfM6ClsbWPKJJIw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNmZ1UDFYMXl4alU&resourcekey=0-uEbQvVcPfM6ClsbWPKJJIw" width="240" alt="1983 - M497B - P011 - 4-1.jpg"></a><br><sub>1983|16 · P011 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1VrOEoxcmM0Rm8/view?resourcekey=0-Lha0OH8tID5Aa0lydniIOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1VrOEoxcmM0Rm8&resourcekey=0-Lha0OH8tID5Aa0lydniIOw" width="240" alt="1983 - M497B - P012 - 8-109-1-1.jpg"></a><br><sub>1983|16 · P012 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG5SNVpGek1JczQ/view?resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG5SNVpGek1JczQ&resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" width="240" alt="1983 - M497B - P013 - 8-109-1-2.jpg"></a><br><sub>1983|16 · P013 - 8-109-1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXRGSER4Z2VZUjg/view?resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXRGSER4Z2VZUjg&resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" width="240" alt="1983 - M497B - P014 - 8-109-2-1.jpg"></a><br><sub>1983|16 · P014 - 8-109-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVhIS1l0dHZTOFk/view?resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVhIS1l0dHZTOFk&resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" width="240" alt="1983 - M497B - P015 - 8-109-2-2.jpg"></a><br><sub>1983|16 · P015 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEhSMFN4X1lnSjg/view?resourcekey=0-51aI3iimlChrQy4-0Vfs7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEhSMFN4X1lnSjg&resourcekey=0-51aI3iimlChrQy4-0Vfs7A" width="240" alt="1983 - M497B - P016 - 8-109-2-3.jpg"></a><br><sub>1983|16 · P016 - 8-109-2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGNLVHZ2c2pzSnc/view?resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGNLVHZ2c2pzSnc&resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" width="240" alt="1983 - M497B - P017 - 8-109-2-4.jpg"></a><br><sub>1983|16 · P017 - 8-109-2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0pTTjJiTU5yOEk/view?resourcekey=0-I38P4wx8KdToHSF039nWHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0pTTjJiTU5yOEk&resourcekey=0-I38P4wx8KdToHSF039nWHA" width="240" alt="1983 - M497B - P018 - 8-109-2-5.jpg"></a><br><sub>1983|16 · P018 - 8-109-2-5</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1983 - M497B - 491-02-002 - ARS FROHT AANEL LEVEL CONTROLS.kicad_sch](KICAD/1983%20-%20M497B%20-%20491-02-002%20-%20ARS%20FROHT%20AANEL%20LEVEL%20CONTROLS.kicad_sch)
- [1983 - M497B - 497-01-003 - OHMS LEFT LEVEL INSERT.kicad_sch](KICAD/1983%20-%20M497B%20-%20497-01-003%20-%20OHMS%20LEFT%20LEVEL%20INSERT.kicad_sch)
- [1983 - M497B - 497-01-003 - OUU ONMS.kicad_sch](KICAD/1983%20-%20M497B%20-%20497-01-003%20-%20OUU%20ONMS.kicad_sch)
- [1983 - M497B - 497-02-002 - CRI TIP.kicad_sch](KICAD/1983%20-%20M497B%20-%20497-02-002%20-%20CRI%20TIP.kicad_sch)
- [1983 - M497B - Dual Master Module (2) p21.kicad_sch](KICAD/1983%20-%20M497B%20-%20Dual%20Master%20Module%20(2)%20p21.kicad_sch)
- [1983 - M497B - Dual Master Module (2) p27.kicad_sch](KICAD/1983%20-%20M497B%20-%20Dual%20Master%20Module%20(2)%20p27.kicad_sch)
- [1983 - M497B - Dual Master Module p21.kicad_sch](KICAD/1983%20-%20M497B%20-%20Dual%20Master%20Module%20p21.kicad_sch)
- [1983 - M497B - Dual Master Module p23.kicad_sch](KICAD/1983%20-%20M497B%20-%20Dual%20Master%20Module%20p23.kicad_sch)
- [1983 - M497B - Dual Master Module p27.kicad_sch](KICAD/1983%20-%20M497B%20-%20Dual%20Master%20Module%20p27.kicad_sch)
- [M497B.kicad_sym](KICAD/M497B.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
