Component selection

EGR 314

Team 302

Tyler Winder, Sam Kohler, Jose Nava-Mesina,Tilak Raj Thanga Raj

**Wind sensor**

**External ADC**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image3.png" style="width:1.04167in;height:0.58333in" /></th>
<th><ul>
<li><blockquote>
<p>Cheapest option of the three</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Only has one channel</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 1</th>
<th><ul>
<li><blockquote>
<p>Best range in input voltage</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Out of range alert feature may cause problems</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>ADC081C027 8-Bit, 189kSPS, 1-Ch SAR ADC with I2C</th>
<th><ul>
<li><blockquote>
<p>Uses I2C</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>May not handle az heat</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$1.141/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.ti.com/product/ADC081C027#order-quality"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image16.png" style="width:2.02083in;height:1.13889in" /></th>
<th><ul>
<li><blockquote>
<p>Has the highest sample rate</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Does not have as large sampling range</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 2</th>
<th><ul>
<li><blockquote>
<p>Has an auto power-down mode when not receiving data</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Temperature range not as high as would like</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th><p>ADS7827</p>
<p>5.25V-2.7V, 8 bit, 250 KSPS, Synchronous Serial ADC</p></th>
<th><ul>
<li><blockquote>
<p>Uses I2C</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Uses an external reference</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$1.879/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.ti.com/product/ADS7827"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image12.png" style="width:1.04167in;height:0.58333in" /></th>
<th><ul>
<li><blockquote>
<p>HaUses I2C more channels can be used for both sensors</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Highest power consumption of the three</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 3</th>
<th><ul>
<li><blockquote>
<p>Has three different modes</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Most expensive</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th><p>ADS7830</p>
<p>8-Bit, 8-Channel Sampling A/D Converter with I2C Interface</p></th>
<th><ul>
<li><blockquote>
<p>Uses I2C</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Large footprint</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$2.333/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.ti.com/product/ADS7830"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

**Choice:** option 1: ADC081C027 8-Bit, 189kSPS, 1-Ch SAR ADC with I2C

**Rationale:** This ADC has the best input voltage range, temperature
range, and is the cheapest of the three.

**Op amp**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image7.png" style="width:1.5625in;height:1.02083in" /></th>
<th><ul>
<li><blockquote>
<p>Has multiple channels so could use both sensors</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Very expensive</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 1</th>
<th><ul>
<li><blockquote>
<p>Great operating temp</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Overly large footprint</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>OPA4991MDYYREP</th>
<th><ul>
<li><blockquote>
<p>Has the highest slew rate</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Will have unused channels</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$10.10/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.mouser.com/ProductDetail/Texas-Instruments/OPA4991MDYYREP?qs=IPgv5n7u5QYEXhSvfh2heg%3D%3D"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image3.png" style="width:1.5625in;height:0.85417in" /></th>
<th><ul>
<li><blockquote>
<p>Has two channels</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Has the lowest slew rate</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 2</th>
<th><ul>
<li><blockquote>
<p>Has the lowest minimum supply voltage</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Has a lower bandwidth</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>OPA2310IDR</th>
<th><ul>
<li><blockquote>
<p>Has a good output current</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Bigger footprint</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$1.22/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.mouser.com/ProductDetail/Texas-Instruments/OPA2310IDR?qs=vvQtp7zwQdO7M4WMfM7rQg%3D%3D"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image5.png" style="width:1.5625in;height:1.29167in" /></th>
<th><ul>
<li><blockquote>
<p>Cheapest option</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Only one channel</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 3</th>
<th><ul>
<li><blockquote>
<p>Smallest size</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Not a very good output current</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>MCP6486UT-E/OT</th>
<th><ul>
<li><blockquote>
<p>Faster bandwidth</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>High offset voltage</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$0.31/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.mouser.com/ProductDetail/Microchip-Technology-Atmel/MCP6486UT-E-OT?qs=tlsG%2FOw5FFghOa1qGRyozQ%3D%3D"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

**Choice:** option 2: OPA2310IDR

**Rationale:** The reason we are choosing this one is it does have two
channels which we can use both sensors through it, and all of its cons
are still within the range of our product.

**DC Generator**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image15.jpg" style="width:2.02083in;height:1.40278in" /></th>
<th><ul>
<li><blockquote>
<p>Contains a holder</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Most expensive</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 1</th>
<th><ul>
<li><blockquote>
<p>Strong wire connections</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Have to buy 5 at a time</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>EUDAX Mini Generator Motors 3V-12V DC Motor</th>
<th><ul>
<li><blockquote>
<p>1500 rpm at 3v</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Can generate power up to 12 v</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$2.00/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.amazon.com/dp/B07CJNXTV1/ref=sspa_dk_detail_0?psc=1&amp;pd_rd_i=B07CJNXTV1&amp;pd_rd_w=vXNZk&amp;content-id=amzn1.sym.88097cb9-5064-44ef-891b-abfacbc1c44b&amp;pf_rd_p=88097cb9-5064-44ef-891b-abfacbc1c44b&amp;pf_rd_r=D82NBFZQH7Z37WH6K6B1&amp;pd_rd_wg=5fFCc&amp;pd_rd_r=a4746478-b933-4151-a5fb-fb326a07dfd1&amp;s=toys-and-games&amp;sp_csd=d2lkZ2V0TmFtZT1zcF9kZXRhaWw&amp;spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyUEFYR0NJTjJXSlhDJmVuY3J5cHRlZElkPUEwMTc3NzkwMjRFWkpQSjFNWEQxSyZlbmNyeXB0ZWRBZElkPUEwOTE5OTI0MURRWkJRSjExRkFHWiZ3aWRnZXROYW1lPXNwX2RldGFpbCZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU="><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image14.jpg" style="width:2.02083in;height:2.19444in" /></th>
<th><ul>
<li><blockquote>
<p>Contain a holder</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Can generate power up to 12 v</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 2</th>
<th><ul>
<li><blockquote>
<p>Strong wire connection</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Has to buy six at a time</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>Sntieecr 6 Set Mini Generator Motors 3V-12V DC Motor</th>
<th><ul>
<li><blockquote>
<p>1500 rpm at 3v</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Contains other items in order.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$1.67/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.amazon.com/dp/B0922N8MCR/ref=syn_sd_onsite_desktop_456?ie=UTF8&amp;psc=1&amp;pd_rd_plhdr=t"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image18.png" style="width:2.02083in;height:1.55556in" /></th>
<th><ul>
<li><blockquote>
<p>Cheapest option</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Weak wire pads</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 3</th>
<th><ul>
<li><blockquote>
<p>Contains a gear</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Does not contain a holder</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th><p>MM10</p>
<p>DC Motor</p></th>
<th><ul>
<li><blockquote>
<p>Reliable</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>16000 rpm at 3v</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">Free from work</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.newark.com/multicomp/mm10/motor-miniature-3v-12000rpm/dp/07WX1229?gclid=CjwKCAiAuOieBhAIEiwAgjCvcq0cNpJg4F_NKq_iuqAnFx3Hu3qtqnRov28cosM5tYGjnvWSh6vzCRoCWg8QAvD_BwE&amp;mckv=_dc%7Cpcrid%7C%7Cplid%7C%7Ckword%7C%7Cmatch%7C%7Cslid%7C%7Cproduct%7C07WX1229%7Cpgrid%7C%7Cptaid%7C%7C&amp;CMP=KNC-GUSA-GEN-SMART-SHOPPING-Private-Label"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

**Choice:** Option 3: MM10 DC Motor

**Rationale:** This product is currently available to us for free and it
does work with previous testing. Option 2 would be a good second option
that would need to be tested.

**Barometric Pressure Sensor**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image13.jpg" style="width:0.83854in;height:0.83854in" /></th>
<th><ul>
<li><blockquote>photo_component/image13.jpg
<p>Tracks temperature and barometric pressure</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Not specifically barometric</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 1</th>
<th><ul>
<li><blockquote>
<p>Customizable setup</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>More expensive</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>ICP-10125 Pressure Sensor</th>
<th><ul>
<li><blockquote>
<p>Easily replaceable</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>More than half the supply voltage needed for power budget</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$7.35 each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.mouser.com/ProductDetail/TDK-InvenSense/ICP-10125?qs=iLbezkQI%252BsjXNGnO2nVjOg%3D%3D"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image17.jpg" style="width:2.02083in;height:2.02778in" /></th>
<th><ul>
<li><blockquote>
<p>Within the 3.3V operating range.</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Absolute pressure readings instead of gauge pressure (needs extra calculations done)</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 2</th>
<th><ul>
<li><blockquote>
<p>22,000 g shock survivability</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Sensitive to electrostatic discharge</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>LPS22HHTR</th>
<th><ul>
<li><blockquote>
<p>I2C and SPI compatible</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Complex readout modes</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$4.37 each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.digikey.com/en/products/detail/stmicroelectronics/LPS22HHTR/9586578"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image2.jpg" style="width:2.02083in;height:2.02778in" /></th>
<th><ul>
<li><blockquote>
<p>Low power mode available just in case</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Readouts based on liquid, not air, requires extra calculations</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 3</th>
<th><ul>
<li><blockquote>
<p>Gives accurate readings</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Most expensive</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>DLC-L20G-U2</th>
<th><ul>
<li><blockquote>
<p>High resolution output</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>May give fuzzy barometric pressure readings</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$48.51 per unit</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.digikey.com/en/products/detail/amphenol-all-sensors-corporation/DLC-L20G-U2/9838292"><u>link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

**Choice:** Option 2: LPS22HHTR

**Rationale:** The LPS22HHTR is the most reliable and inexpensive of the
few options available for these types of sensors, and requires the least
amount of calculations to be done in post compared to the other two.
Option 1 would be a good fallback if needed.

**Voltage Regulator**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image4.png" style="width:1.83854in;height:1.84802in" /></th>
<th><ul>
<li><blockquote>
<p>Supplies fixed voltage</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Low Stock</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 1</th>
<th><ul>
<li><blockquote>
<p>6 week Lead time</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Low current output</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>LM3671MF-3.3/NOPB</th>
<th><ul>
<li><blockquote>
<p>Good operating temperature</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Low voltage range</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$1.74/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.digikey.com/en/products/detail/texas-instruments/LM3671MF-3-3-NOPB/1590062?utm_adgroup=Texas%20Instruments&amp;utm_source=google&amp;utm_medium=cpc&amp;utm_campaign=Dynamic%20Search_EN_Focus%20Suppliers&amp;utm_term=&amp;utm_content=Texas%20Instruments&amp;gclid=CjwKCAiAuOieBhAIEiwAgjCvcgl6FrHKzpFOkemhengFJNIQXtg4rm4Tnn96wR-nfu4zoRnv-GSeiBoCv-wQAvD_BwE"><u>Link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image8.png" style="width:0.90104in;height:0.90104in" /></th>
<th><ul>
<li><blockquote>
<p>Good voltage range</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Expensive</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 1</th>
<th><ul>
<li><blockquote>
<p>Best range in input voltage</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Low stock</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>LM2594HVM-5.0/NOPB</th>
<th><ul>
<li><blockquote>
<p>Larger part easier to solder</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Low current output</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$6.65/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.digikey.com/en/products/detail/texas-instruments/LM2594HVM-5-0-NOPB/363684"><u>Link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Solution</th>
<th>Pros</th>
<th>Cons</th>
</tr>
<tr class="odd">
<th><img src="photo_component/image6.png" style="width:0.73141in;height:0.73518in" /></th>
<th><ul>
<li><blockquote>
<p>Good voltage range</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Most expensive</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th>Option 1</th>
<th><ul>
<li><blockquote>
<p>Best current output</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Smaller pins</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>LM2596S-3.3/NOPB</th>
<th><ul>
<li><blockquote>
<p>High stock</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>May be difficult to solder</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3">$1.141/each</th>
</tr>
<tr class="odd">
<th colspan="3"><a href="https://www.digikey.com/en/products/detail/texas-instruments/LM2596S-3-3-NOPB/363704?utm_adgroup=Texas%20Instruments&amp;utm_source=google&amp;utm_medium=cpc&amp;utm_campaign=Dynamic%20Search_EN_Focus%20Suppliers&amp;utm_term=&amp;utm_content=Texas%20Instruments&amp;gclid=CjwKCAiAuOieBhAIEiwAgjCvcv1RQACvc7eoyc5kEUeOsHC-rdM7IOU5Q3M5odXNLbipteF3X3QPeBoCF1kQAvD_BwE"><u>Link</u></a></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

**Choice:** LM2596S-3.3/NOPB

**Rationale:** Best choice in terms of operation and for what our design
needs. May be a bit on the expensive side but it covers all the bases
where some of the other components fall a bit short with good stock
availability. .

## Motor System - Tilak

**Motor Driver**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Solution</strong></p>
<p><img src="photo_component/image10.png" style="width:2.02083in;height:2.02778in" /></p>
<p>Option 1</p>
<p>IFX9201SGAUMA1</p>
<p>DC H Bridge Driver</p>
<p>$4.88/each</p>
<p><a href="https://www.digikey.com/en/products/detail/infineon-technologies/IFX9201SGAUMA1/5415542"><u>From Digikey</u></a></p></th>
<th><p><strong>Pros</strong></p>
<ul>
<li><blockquote>
<p>Supports SPi</p>
</blockquote></li>
<li><blockquote>
<p>Can operate at 3.3V logic levels</p>
</blockquote></li>
<li><blockquote>
<p>Includes internal flyback diodes</p>
</blockquote></li>
</ul></th>
<th><p><strong>Cons</strong></p>
<ul>
<li><blockquote>
<p>No physical heatsink</p>
</blockquote></li>
<li><blockquote>
<p>Requires heatsink pad on PCB</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th><h1 id="section"><img src="photo_component/image9.png" style="width:1.5625in;height:1.09375in" /></h1>
<p>Option 2</p>
<p>MCF8315A1VRGFR</p>
<p>DC H Bridge Driver</p>
<p>$4.50/each</p>
<p><a href="https://www.mouser.com/ProductDetail/Texas-Instruments/MCF8315A1VRGFR?qs=rQFj71Wb1eW9Q9rSU7C3NQ%3D%3D"><u>From Mouser</u></a></p></th>
<th><ul>
<li><blockquote>
<p>FOC controller Three-phase BLDC motor driver</p>
</blockquote></li>
<li><blockquote>
<p>Anti-voltage surge (AVS) protection</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Does not support SPI</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th><p><img src="photo_component/image1.png" style="width:1.52083in;height:1.23958in" /></p>
<p>Option 3</p>
<p>BD6210HFP-TR</p>
<p>DC H Bridge Driver</p>
<p>$1.99/each</p>
<p><a href="https://www.digikey.com/en/products/detail/rohm-semiconductor/BD6210HFP-TR/1936301"><u>From Digikey</u></a></p></th>
<th><ul>
<li><blockquote>
<p>Cheap</p>
</blockquote></li>
<li><blockquote>
<p>VREF Voltage Setting Pin Enables PWM Duty Control</p>
</blockquote></li>
</ul></th>
<th><ul>
<li><blockquote>
<p>Does not support SPI</p>
</blockquote></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

**Choice:** Option 1: IFX9201SGAUMA1

**Rationale:** SPI is only provided in the above motor driver. Also
includes a flyback diode.
