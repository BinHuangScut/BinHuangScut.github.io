---
layout: page
permalink: /statistics/
title: "Visitor Statistics"
nav: true
nav_order: 9
---

{% if site.clustrmaps_src %}

<div class="visitor-map-wrapper" style="min-height: 400px; width: 100%;">
  <script type="text/javascript" id="clustrmaps" src="{{ site.clustrmaps_src }}"></script>
</div>
<noscript><a href="https://clustrmaps.com/site/1c99a" title="ClustrMaps"><img src="https://www.clustrmaps.com/map_v2.png?d=Kq5GcIykQsC0v_dFcW4gdy4oSTha7cw8ZLzPrjmYqKU&cl=ffffff" alt="Visitor map" style="max-width: 100%;"></a></noscript>
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
