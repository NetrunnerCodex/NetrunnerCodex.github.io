---
parent: test
slug_title: Test
slug_title: Testing
slug_subtitle: 123
slug_image: "/assets/images/slugs/nrcx-slug.png"
layout: default
has_children: false
nav_order:
---
<div class="slug unified-background">
    <div class="slug-left">
        <h1 class="page-slug_title">{{ page.slug_title }}</h1>
        <p class="page-slug_subtitle">{{ page.slug_subtitle }}</p>
    </div>
    <div class="slug-right">
        <img src="{{ page.slug_image | relative_url }}" alt="{{ page.title }}" />
    </div>
</div>

<span class="text-grey-dk-000 fs-9 fw-700">TEST</span>

<div class="tables-container">
  <div class="table-group">
    <h2>Corp Symbols</h2>
    <table class="sml-table">
      <tr>
        <td><span class="nric-blue haas"></span></td>
        <td>Haas-Bioroid</td>
      </tr>
      <tr>
        <td><span class="nric-blue jinteki"></span></td>
        <td>Jinteki</td>
      </tr>
      <tr>
        <td><span class="nric-blue nbn"></span></td>
        <td>NBN</td>
      </tr>
      <tr>
        <td><span class="nric-blue weyland"></span></td>
        <td>Weyland Consortium</td>
      </tr>
    </table>
  </div>

  <div class="table-group">
    <h2>Runner Symbols</h2>
    <table class="sml-table">
      <tr>
        <td><span class="nric-red anarch"></span></td>
        <td>Anarch</td>
      </tr>
      <tr>
        <td><span class="nric-red criminal"></span></td>
        <td>Criminal</td>
      </tr>
      <tr>
        <td><span class="nric-red shaper"></span></td>
        <td>Shaper</td>
      </tr>
    </table>
  </div>
</div>

