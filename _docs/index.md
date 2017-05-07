---
layout: docs
title: Analyze average flat prices
---
Let's say we plan to buy a flat in London in 'N13 4' postcode sector. We can see this
sector in more details:

<ol>
    <li>Type 'N13 4' in the search field, hit enter.</li>
    <li>Select 'flat' from the filter menu.</li>
    <li>Click on the sector with a black border.</li>
</ol>
'N13 4' house card pops up.

[![North London house price map](/img/tut1.1.png)](http://a.plumplot.co.uk?tab=map1&pt=2&pc=157&yr=-13)

The first tab 'Area comparison' of the house card compares selected postcode
sector (or postcode district) - 'N13 4' to its postcode area (N).

We can see that an average flat price for the last year is £313k.
'N' area is a bit more expensive with an average price of £442k.

In the last 12 months, price grew slower in 'N13 4' (3.3%) than in N postcode area (6.6%).
However, growth is taken from 65 properties. The volume of
sold properties is too low. When determining price growth
the volume should be always at least 100 properties (better 500).

We can compare 'N13' postcode district to 'N' area.

* Select <code>houses</code> &#187; <code>avg. price % change</code>

[![Annual flat price changes in London](/img/tut1.2.png)](http://a.plumplot.co.uk?tab=map2&pt=2&pc=157&yr=-13)

An average flat price grew up by 1.2% in 'N13' district. 'Avg. price change' map is the only map
with an area boundary is on postcode district level only. In all other
maps, you can see metrics on postcode sector level. For a price change the volume
of sold properties is usually too low for postcode sector (sometimes even district is too small for price change).

You can also see how 'N13' correlates to other 'N' areas

* select <code>houses</code> &#187; <code>area correlation</code> dashboard.

[![Flat sales volume in North London](/img/tut1.3.png)](http://a.plumplot.co.uk?tab=procor&pt=2&pc=157&yr=-13)

By zooming in the graph you can find out that 'N13' district
is (has been) one of the cheapest districts in 'N' area.
It's the one with the lowest price growth. However not many
flats are sold in this district (the circle is relatively small compared
to other circles).
