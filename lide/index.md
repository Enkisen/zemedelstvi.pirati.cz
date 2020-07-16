---
layout: members
title: Tým Zemědělství
description:  My jsme zemědělci, lesníci, rolníci, rybáři, myslivci, včelaří, zahrádkáři, piráti, pirátky, chovatelé.
keywords: zemědělci, lesníci, rolníci, rybáři, myslivci, včelaři, zahrádkáři, chovatelé, piráti, pirátky, příznivci
---

<div class="row">
  <div class="columns">
    <div class="o-section">
      <div class="o-section-inner">
          <header class="c-page-header">
            {% assign garant = site.people | where: "category", "garant" %}
            <h1 itemprop="headline" class="c-page-title">{{ garant.name }}Garant programového bodu</h1>
          </header>
          <hr><h1 itemprop="headline" class="c-page-title">Poslanci resortu zemědělství</h1>
          {% for clen in site.people  | where: "category", "poslanec" %}
            <p><img src="{{ clen.img }}"><b>{{ clen.name }}</b> - {{ clen.description | markdownify}}</p>
          {% endfor %}
          <hr><h1 itemprop="headline" class="c-page-title">Experti Středočeský kraj</h1>
          {% for clen in site.people  | where: "category", "středočeský" %}
            <p><img src="{{ clen.img }}"><b>{{ clen.name }}</b> - {{ clen.description | markdownify}}</p>
          {% endfor %}        
          <hr><h1 itemprop="headline" class="c-page-title">Experti Hl.m. Praha</h1>
          {% for clen in site.people  | where: "category", "středočeský" %}
            <p><img src="{{ clen.img }}"><b>{{ clen.name }}</b> - {{ clen.description | markdownify}}</p>
          {% endfor %}   
          <hr><h1 itemprop="headline" class="c-page-title">Experti Kraj Vysočina</h1>
          {% for clen in site.people  | where: "category", "středočeský" %}
            <p><img src="{{ clen.img }}"><b>{{ clen.name }}</b> - {{ clen.description | markdownify}}</p>
          {% endfor %}   
        <hr>
      </div>
    </div>
  </div>
</div>
