<div class="nav">
    <div class="nav-left">
        <a href="#">
            <div class="home-button">
                <img src="/huisstijlgids/assets/img/WitTP_crop.png" class="img-fluid">
            </div>
        </a>
    </div>
    <div class="nav-right">
    {% for item in site.data.navitems.docs %}
      <a class="{% if item.url == page.url %}active{% endif %}" href="{{ item.url }}"  {% page.url %}>{{ item.title }}</a>
   {% endfor %}
        <!-- <a href="/huisstijlgids">Home</a>
        <a href="/huisstijlgids/logo">Logo</a>
        <a href="/huisstijlgids/typo">Typografie</a>
        <a href="/huisstijlgids/icons">Icons</a>
        <a href="/huisstijlgids/colors">Kleuren</a>
        <a href="/huisstijlgids/print">Print</a>
        <a href="/huisstijlgids/digital">Digitaal</a> -->
    </div>
</div>
