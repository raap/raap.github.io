---
layout: docs
title: Data
permalink: /docs/data/
---
The data is usually released with a month delay (ie. properties sold in January are released at the end of February), with some records delayed for up to 3 months. Ie. if you want to see all sales for 2015, you need to wait until the end of March 2016. We use the latest UK government data released under <a href="http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/" target="_blank">OGL v3.0</a>. 

<div class="mobile-side-scroller">
<table>
  <thead>
    <tr>
      <th>Data</th>
      <th>Released</th>
      <th>First record</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><p><a href="https://www.gov.uk/government/organisations/land-registry" target="_blank">Land Registry</a></p></td>
      <td><p>each month</p></td>
      <td><p>1995-01</p></td>
    </tr>
    <tr>
      <td><p><a href="https://data.police.uk" target="_blank">The UK police data</a></p></td>
      <td><p>each month</p></td>
      <td><p>2010-12</p></td>
    </tr>
    <tr>
      <td><p><a href="http://www.nomisweb.co.uk/census/2011">Census 2011</a></p></td>
      <td><p>once</p></td>
      <td><p>2011</p></td>
    </tr>
  </tbody>
</table>
</div>

### Land Registry

<a href="https://www.gov.uk/guidance/about-the-price-paid-data" target="_blank">Price Paid Dataset</a> is the most reliable open data source about the residential property sales.
It includes over 20 million property sales since 1995. I.e. ~1 million sales transaction per year.

### Police data

includes over 30 million crime records since 2010-12. I.e. ~6 million committed crimes per year.

### 2011 Census data

From census 2011 we use postcode headcount and a workday population.
Postcode headcounts are the only Census statistics that are available for full postcodes.

<div class="note warning">
The workday population is collected for output areas. In some cases, these
areas do not align with the postcode sector boundaries. In this situation,
we approximate a number of workday population. In most cases the approximate 
number is precise, nevertheless, for very small postcodes the error can
be significant.
</div>

Comparing census data in 2001 and 2011, significant population change
occurred in 2.6% (based on output areas units).
