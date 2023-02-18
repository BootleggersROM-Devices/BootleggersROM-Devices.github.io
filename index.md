---
layout: default
title: Downloads
---
<div class="card shishu-light-bg z-depth-3">
  <div class="card-content">
    <span class="card-title">Welcome to our downloads</span>
    <p>This is where all our officially supported devices are listed. If the device you're looking for isn't on the list, please check your build type (all the official releases are Shishufied) or ask your device maintainer to talk to us on our <a href="https://t.me/keepthebootleg">Telegram Chat.</a> Also, you can check our <a href="https://bootleggersrom.github.io/extras/addons">suggested addons and apps</a> that you might find interesting.</p>
  </div>
</div>
<div class="card shishu-light-bg z-depth-3">
  <div class="card-content">
    <span class="card-title">Releases</span>
    <ul class="collapsible shishu-lighter-bg collapsible-noborder">
      {% assign devicelistsize = site.devices | size %} {% if devicelistsize > 0 %} {% for device in site.devices %}
        <li>
          <div class="collapsible-header collapsible-noborder shishu-lighter-bg">
            <i class="material-icons">phone_android</i>
          {{ device.codename }} | {{ device.fullname }}</div>
          <div class="collapsible-body collapsible-noborder shishu-midlight-bg">
            <span>Maintainer:</span><div class="chip shishu-lighter-bg" style="margin-left:4px">{{ device.maintainer }}</div><br>
            <span>Latest build:</span><div class="chip shishu-lighter-bg" style="margin-left:4px">{{ device.filename }}</div><br>
            <span>Build size:</span><div class="chip shishu-lighter-bg" style="margin-left:4px">{{ device.buildsize | divided_by: 1048576 }}MB</div><br><br>
            <a class="waves-effect waves-light btn-small shishu-accent-btn" href="https://sourceforge.net/projects/bootleggersrom/files/builds/{{ device.codename }}/{{ device.filename }}"><i class="material-icons left">get_app</i>Download</a>
            {% if device.mirrorlink %}
              <a class="waves-effect waves-light btn-small shishu-accent-btn" href="{{ device.mirrorlink }}"><i class="material-icons left">open_in_new</i>Mirror</a>
            {% endif %}
            <a class="waves-effect waves-light btn-small shishu-accent-btn" href="https://sourceforge.net/projects/bootleggersrom/files/builds/{{ device.codename }}"><i class="material-icons left">history</i>Older Builds</a>
            {% if device.xdathread %}
              <a class="waves-effect waves-light btn-small shishu-accent-btn" href="{{ device.xdathread }}"><i class="material-icons left">library_books</i>XDA Thread</a>
            {% endif %}
            <a class="waves-effect waves-light btn-small shishu-accent-btn modal-trigger" href="#modal-chlg-{{device.codename}}"><i class="material-icons left">receipt</i>Changelog</a>
          </div>
        </li>
        <!-- Modal for {{device.codename}} -->
        <div id="modal-chlg-{{device.codename}}" class="modal modal-fixed-footer shishu-light-bg">
          <div class="modal-content">
              <h4>Changelog for {{ device.codename }}</h4>
              <div class="chlg-code cl-code-{{ device.codename }}"></div>
        </div>
          <div class="modal-footer shishu-light-bg">
            <a href="#!" class="modal-close waves-effect waves-light btn-flat">Close</a>
          </div>
        </div>
        <script>
        $(document).ready(function(){
         $('#modal-chlg-{{device.codename}}').modal(
           {onOpenEnd: getChangelog('{{device.codename}}')
           });
         });
        </script>
      {% endfor %}
      {% else %}
      <h3>Currently, we don't have any shishufied releases</h3>
      <p>Check this site later, we're working on having a cool release for you :)</p>{% endif %}
    </ul>
  </div>
</div>
