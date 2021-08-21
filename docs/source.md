## Functions

<dl>
<dt><a href="#body2latlong">body2latlong(body)</a> ⇒ <code>Object</code></dt>
<dd></dd>
<dt><a href="#date2julian">date2julian(date)</a> ⇒ <code>Number</code></dt>
<dd><p>Function that generates the Julian date from a traditional date time format more info about Juñian dates:</p>
</dd>
<dt><a href="#deg2rad">deg2rad(x)</a> ⇒ <code>Number</code> | <code>Number</code></dt>
<dd></dd>
<dt><a href="#mod">mod(n, m)</a> ⇒ <code>Number</code></dt>
<dd></dd>
<dt><a href="#rad2deg">rad2deg()</a></dt>
<dd><p>Astrodynamics | Kepler Solver
Author: Edgar Gago Carrillo
Date 16/03/2021</p>
<p>Inputs:
variable in rad</p>
<p>Outputs:
x but in degrees</p>
<p>Description:
From degrees to rad</p>
</dd>
<dt><a href="#trueanom">trueanom()</a></dt>
<dd><p>Astrodynamics | Kepler Solver
Author: Edgar Gago Carrillo
Date 16/03/2021</p>
<p>Description
Computation of the true anomally</p>
<p>Inputs
ibt: orbital elements {}
E: eccentric anomaly [rad]</p>
<p>Ouputs
theta: true anomaly [rad]</p>
</dd>
</dl>

<a name="body2latlong"></a>

## body2latlong(body) ⇒ <code>Object</code>
**Kind**: global function  

| Param | Type |
| --- | --- |
| body | <code>\*</code> | 

<a name="date2julian"></a>

## date2julian(date) ⇒ <code>Number</code>
Function that generates the Julian date from a traditional date time format more info about Juñian dates:

**Kind**: global function  
**Returns**: <code>Number</code> - JD - JD: Julian Day  
**Docs**: // Core // date2julian  

| Param | Type | Description |
| --- | --- | --- |
| date | <code>Date</code> | Calendar date format: year, month, day, hour, minute, second |

<a name="deg2rad"></a>

## deg2rad(x) ⇒ <code>Number</code> \| <code>Number</code>
**Kind**: global function  

| Param | Type |
| --- | --- |
| x | <code>\*</code> | 

**Example**  
```js
// returns 3.14
deg2rad(90);
```
<a name="mod"></a>

## mod(n, m) ⇒ <code>Number</code>
**Kind**: global function  

| Param | Type |
| --- | --- |
| n | <code>\*</code> | 
| m | <code>\*</code> | 

<a name="rad2deg"></a>

## rad2deg()
Astrodynamics | Kepler Solver
Author: Edgar Gago Carrillo
Date 16/03/2021

Inputs:
variable in rad

Outputs:
x but in degrees

Description:
From degrees to rad

**Kind**: global function  
<a name="trueanom"></a>

## trueanom()
Astrodynamics | Kepler Solver
Author: Edgar Gago Carrillo
Date 16/03/2021

Description
Computation of the true anomally

Inputs
ibt: orbital elements {}
E: eccentric anomaly [rad]

Ouputs
theta: true anomaly [rad]

**Kind**: global function  
