# SVG-Tables

Легковестные SVG таблицы

### Текущая версия (https://github.com/ChaoS-LogiC/SVG-Table/releases)

## Быстрый старт


```
<div>
<svg width="100%" height="100%" viewBox="0 0 370 160">
<title>Tables</title>

<g id='rowGroup' transform='translate(0, 0)' role="table">
<rect x='25' y='40' width='310' height='20' fill='gainsboro'/>
<rect x='25' y='76' width='310' height='20' fill='gainsboro'/>

<text x='30' y='30' font-size='18px' font-weight='bold' fill='crimson' text-anchor='middle' role="row">
<tspan role="columnheader" x='100'>1 значение</tspan>
<tspan  role="columnheader" x='200'>2 значение</tspan>
<tspan role="columnheader" x='300'>3 значение</tspan>
</text>

<text x='30' y='30' font-size='18px' text-anchor='middle' role="row">
<tspan role="rowheader" x='30' dy='1.5em' font-weight='bold' fill='crimson' text-anchor='start'>111</tspan>
<tspan role="cell" x='100'>$ 223</tspan>
<tspan role="cell" x='200'>$ 195</tspan>
<tspan role="cell" x='300'>$ 28</tspan>
</text>

<text x='30' y='30' font-size='18px' text-anchor='middle' role="row">
<tspan role="rowheader" x='30' dy='2.5em' font-weight='bold' fill='crimson' text-anchor='start'>222</tspan>
<tspan role="cell" x='100'>$ 183</tspan>
<tspan role="cell" x='200'>$ 70</tspan>
<tspan role="cell" x='300'>$ 113</tspan>
</text>

<text x='30' y='30' font-size='18px' text-anchor='middle' role="row">
<tspan role="rowheader" x='30' dy='3.5em' font-weight='bold' fill='crimson' text-anchor='start'>333</tspan>
<tspan role="cell" x='100'>$ 277</tspan>
<tspan role="cell" x='200'>$ 88</tspan>
<tspan role="cell" x='300'>$ 189</tspan>
</text>

<text x='30' y='30' font-size='18px' text-anchor='middle' role="row">
<tspan id="q4" role="rowheader" x='30' dy='4.5em' font-weight='bold' fill='crimson' text-anchor='start'>444</tspan>
<tspan role="cell" x='100'>$ 402</tspan>
<tspan role="cell" x='200'>$ 133</tspan>
<tspan role="cell" x='300'>$ 269</tspan>
</text>
</g>
</svg>
</div>
```
