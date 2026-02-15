---
layout: page
permalink: /statistics/
title: "Visitor Statistics"
nav: true
nav_order: 9
---

This page shows **total pageviews** and an interactive **visitor location map** (similar to [TBendong's site](https://tbendong.github.io/)).

{% if site.clustrmaps_src %}
<p class="text-muted"><strong>Total pageviews</strong> and visitor locations are shown in the map below. Click the map to zoom and explore.</p>
<div class="visitor-map-wrapper" id="clstr_globe" style="height: 520px; min-height: 520px; margin-top: 1rem; width: 100%;">
  <script type="text/javascript" src="{{ site.clustrmaps_src }}"></script>
</div>
<noscript>Enable JavaScript to view the visitor map.</noscript>
{% else %}
<div class="visitor-stats-setup">
  <p><strong>Total pageviews</strong> and the <strong>visitor map</strong> can be displayed here after a one-time setup. Choose one of the following:</p>
  <ol>
    <li>
      <strong>ClustrMaps (free, embeddable)</strong> — Get a free widget at <a href="https://clustrmaps.com" target="_blank" rel="noopener">clustrmaps.com</a>: add your site URL, then copy the script <code>src</code> URL (e.g. <code>//cdn.clustrmaps.com/map_v2.js?d=xxxxx</code>). In <code>_config.yml</code>, set <code>clustrmaps_src: "your-copied-url"</code> and rebuild the site. The map and pageview count will appear above.
    </li>
    <li>
      <strong>OpenPanel (full dashboard)</strong> — Create an account at <a href="https://dashboard.openpanel.dev/onboarding" target="_blank" rel="noopener">OpenPanel</a>, create a project, and copy your client ID. In <code>_config.yml</code>, set <code>openpanel_analytics: "your-client-id"</code> and <code>enable_openpanel_analytics: true</code>. Your dashboard at <a href="https://dashboard.openpanel.dev" target="_blank" rel="noopener">dashboard.openpanel.dev</a> will show total pageviews, an interactive geo map, and more. (The map and count are viewed on OpenPanel’s site; this page can stay as a link to that dashboard if you prefer.)
    </li>
  </ol>
</div>
{% endif %}
