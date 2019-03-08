## How to support your scale

If you want to help to support your Bluetooth scale please see [here](How-to-reverse-engineer-a-Bluetooth-4.x-scale) for further information.

## Overview

<table>
<tr>
<td><b>Scale</b></td>
<td align="center"><b>Initialisation process</b></td>
<td align="center"><b>History data</b></td>
<td align="center"><b>Body metrics</b></td>
<td><b>Remarks / Known Issues</b></td>
</tr>
<tr>
<td>Custom openScale</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td>see <a href="Custom-Bluetooth-Scale">here</a> for a tutorial</td>
</tr>
<tr>
<td>Xiaomi Mi scale v1</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td>No data on the scale is ever deleted</td>
</tr>
<tr>
<td>Medisana BS430/BS444/BS440</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>Sanitas SBF70</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td>assigned user name on the scale and in openScale have to be the same, see 
<a href="Frequently-Asked-Questions-(FAQ)#how-do-i-get-on-my-sbf70-scale-the-body-metrics-water-muscle-fat-percentage">FAQ</a></td>
</tr>
<tr>
<td>Digoo DG-S038H</td>
<td align="center">o</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>Initialisation process needs to be reverse engineered. Currently you have to use one time the vendors app to initialise the scale.</td>
</tr>
<tr>
<td>Yunmai Mini / Yunmai Premium</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>Excelvan CF369BLE</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>Yunmai SE</td>
<td align="center">o</td>
<td align="center">n/a</td>
<td align="center">n/a</td>
<td>Weight unit is currently not set via openScale</td>
</tr>
<tr>
<td>MGB / Vitalmaxx</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>Xiaomi Mi scale v2</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">o</td>
<td>Only the weight are supported by openScale. The body fat, water and LBM of the body metrics are currently <a href="https://github.com/oliexdev/openScale/wiki/Body-metric-estimations">estimated</a> until the reverse engineering of the used library</td>
</tr>
<tr>
<td>Exingtech Y1</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>Beurer BF700/710/800</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>Silvercrest SBF75</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td>assigned user name on the scale and in openScale have to be the same, see 
<a href="Frequently-Asked-Questions-(FAQ)#how-do-i-get-on-my-sbf70-scale-the-body-metrics-water-muscle-fat-percentage">FAQ</a></td>
</tr>
<tr>
<td>Runtastic Libra</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>Hesley (Yunchen)</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>iHealth HS3</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">n/a</td>
<td>-</td>
</tr>
<tr>
<td>Easy Home 64050</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>Accuway</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>OneByone</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>Trisa Body Analyze 4.0</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<tr>
<td>Inlife</td>
<td align="center">&#10003;</td>
<td align="center">n/a</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
<td>FITINDEX ES-26M</td>
<td align="center">&#10003;</td>
<td align="center">o</td>
<td align="center">&#10003;</td>
<td>-</td>
</tr>
</table>
&#10003; : supported in openScale <br>
o : supported by the scale but still needs to be reverse engineered<br>
n/a : not available on the scale 

<!-- DivTable.com -->

## Detailed information

_Please select a scale for further information_

<table border="0" align="center">
  <tr>

<th>
<a href="Custom-Bluetooth-Scale">
<img src='../raw/master/doc/custom_scale/parts/scale_hacked_front.JPG' width='270px' alt='image missing' /> </a> <br>
<sub><a href="Custom-Bluetooth-Scale">Custom Bluetooth scale</a></sub>
</th>

<th>
<a href="Xiaomi-Bluetooth-Mi-Scale">
<img src='../raw/master/doc/scales/miscale.jpg' width='200px' alt='image missing' /> </a> <br>
<sub><a href="Xiaomi-Bluetooth-Mi-Scale">Xiaomi Mi scale v1</a></sub>
</th>

  </tr>

  <tr>

<th>
<a href="Medisana-BS444">
<img src='../raw/master/doc/scales/medisana_bs444.jpg' width='250px' alt='image missing' /> </a> <br>
<sub><a href="Medisana-BS444">Medisana BS444 scale</a></sub>
</th>

<th>
<a href="Beurer-Sanitas">
<img src='../raw/master/doc/scales/sanitas_sbf70.jpg' width='280px' alt='image missing' /></a> <br>
<sub><a href="Beurer-Sanitas">Sanitas SBF70</a></sub>
</th>

  </tr>

  <tr>

<th>
<img src='../raw/master/doc/scales/Digoo%20DG-S038H.jpeg' width='250px' alt='image missing' /> <br>
<sub>Digoo DG-S038H</sub>
</th>

<th>
<img src='../raw/master/doc/scales/yunmai_mini.jpg' width='250px' alt='image missing' /> <br>
<sub>Yunmai Mini</sub>
</th>
</tr>

<tr>
<th>
<img src='../raw/master/doc/scales/excelvan_cf369ble.jpg' width='250px' alt='image missing' /> <br>
<sub>Excelvan CF369BLE</sub>
</th>

<th>
<img src='../raw/master/doc/scales/yunmai_se.jpeg' width='250px' alt='image missing' /> <br>
<sub>Yunmai SE</sub>
</th>

  </tr>
</tr>

<tr>
<th>
<img src='../raw/master/doc/scales/mgb.jpg' width='250px' alt='image missing' /> <br>
<sub>MGB</sub>
</th>

<th>
<br>
<img src='../raw/master/doc/scales/mi_scalev2.jpg' width='250px' alt='image missing' /> <br>
<sub>Xiaomi Mi scale v2</sub>
</th>

  </tr>
<tr>
<th>
<img src='../raw/master/doc/scales/exingtech_y1.jpg' width='250px' alt='image missing' /> <br>
<sub>Exingtech Y1</sub>
</th>

<th>
<a href="Beurer-Sanitas">
<img src='../raw/master/doc/scales/beurer_bf700.jpg' width='300px' alt='image missing' /></a> <br>
<sub><a href="Beurer-Sanitas">Beurer BF700/800</a></sub>
</th>

  </tr>

<tr>
<th>
<a href="Beurer-Sanitas">
<img src='../raw/master/doc/scales/silvercrest_sbf75.jpg' width='250px' alt='image missing' /></a> <br>
<sub><a href="Beurer-Sanitas">Silvercrest SBF75</a></sub>
</th>

<th>
<img src='../raw/master/doc/scales/runtastic.jpg' width='300px' alt='image missing' /> <br>
<sub>Runtastic Libra</sub>
</th>

  </tr>

<tr>
<th>
<img src='../raw/master/doc/scales/hesley.jpg' width='250px' alt='image missing' /> <br>
<sub>Hesley (Yunchen) scale</sub>
</th>

<th>
<img src='../raw/master/doc/scales/ihealth_hs3.jpg' width='300px' alt='image missing' /> <br>
<sub>iHealth HS3</sub>
</th>

  </tr>
<tr>
<th>
<img src='../raw/master/doc/scales/beurer_bf710.jpg' width='300px' alt='image missing' /> <br>
<sub>Beurer BF710</sub>
</th>

<th>
<img src='../raw/master/doc/scales/easy_home_64050.jpg' width='300px' alt='image missing' /> <br>
<sub>Easy Home 64050</sub>
</th>
  </tr>

<tr>
<th>
<img src='../raw/master/doc/scales/medisana_bs440.jpg' width='300px' alt='image missing' /> <br>
<sub>Medisana BS440</sub>
</th>

<th>
<img src='../raw/master/doc/scales/accuway.jpg' width='300px' alt='image missing' /> <br>
<sub>Accuway</sub>
</th>

</tr>

<tr>
<th>
<img src='../raw/master/doc/scales/excelvan_cf366ble.jpg' width='300px' alt='image missing' /> <br>
<sub>Excelvan CF366BLE</sub>
</th>

<th>
<a href="Trisa-Body-Analyze">
<img src='../raw/master/doc/scales/trisa_body_analyze.jpg' width='300px' alt='image missing' /></a><br>
<sub><a href="Trisa-Body-Analyze">Trisa Body Analyze 4.0</a></sub>
</th>

</tr>

<tr>

<th>
<img src='../raw/master/doc/scales/inlife.jpg' width='300px' alt='image missing' /> <br>
<sub>Inlife</sub>
</th>
</tr>
<tr>
<th>
<img src='../raw/master/doc/scales/fitindex_es26m.jpg' width='300px' alt='image missing' /> <br>
<sub>FITINDEX ES-26M</sub>
</th>
</tr>
</table>
