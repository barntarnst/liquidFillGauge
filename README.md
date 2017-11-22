# liquidFillGauge
Liquid fill graph library

Update of D3 Liquid Fill Gauge by Curtis Bratton see http://bl.ocks.org/brattonc/5e5ce9beee483220e2f6

For d3 v4

Example of use

html
```javascript
<svg id="my-chart" width="73" height="73"></svg>
```
javascript
```javascript
import liquidFillGauge from 'YOUR/PATH/liquidFillGauge'
import * as d3 from 'd3'

var conf = liquidFillGauge.default()
conf.circleColor = '#F7C22D'
conf.textColor = '#F7C22D'
conf.waveTextColor = '#FFE9B3'
conf.waveColor = '#F7C22D'
conf.displayPercent = true
conf.maxValue = 100
conf.waveCount = 2
conf.circleThickness = 0.1
conf.waveAnimateTime = 2400
liquidFillGauge.load(d3, 'my-chart', 50, config)
```
