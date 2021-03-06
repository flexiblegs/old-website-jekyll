---
layout: flexiblegs
dynamic_title: compatibility
permalink: /compatibility/
---

<div class="dn-browser">
  <div class="dn-browser-header">
    <div class="dn-style--title">{{ site.t.[page.language].[page.dynamic_title].title }}</div>
    {% include flexiblegs/logo.html %}
  </div>
  <div class="dn-browser-body">
    <div class="dn-browser-body__item">
      <div class="wrap xl-table xl-gutter-40 xl-top xl-center md-normal">
        <div class="col xl-width-360 md-1-1">
          {% include flexiblegs/social-media.html %}
        </div>
        <div class="col xl-1-1">
          <div class="dn-content">
            <div class="wrap xl-gutter-24 xl-top xl-2 md-1">
              <div class="col">
                {% if page.language == 'en' %}
                  <p><b>Browser</b></p>
                {% endif %}
                {% if page.language == 'tr' %}
                  <p><b>Tarayıcı</b></p>
                {% endif %}
                <div class="dn-height-16"></div>
                <ul>
                  <li>IE 9+</li>
                  <li>Chrome</li>
                  <li>Firefox</li>
                  <li>Safari</li>
                  <li>Opera</li>
                </ul>
                <div class="dn-height-16"></div>
              </div>
              <div class="col">
                {% if page.language == 'en' %}
                  <p><b>Framework</b></p>
                {% endif %}
                {% if page.language == 'tr' %}
                  <p><b>Framework</b></p>
                {% endif %}
                <div class="dn-height-16"></div>
                {% if page.language == 'en' %}
                  <ul>
                    <li>Bootstrap</li>
                    <li>Foundation and more :)</li>
                  </ul>
                {% endif %}
                {% if page.language == 'tr' %}
                  <ul>
                    <li>Bootstrap</li>
                    <li>Foundation ve daha fazlası :)</li>
                  </ul>
                {% endif %}
                <div class="dn-height-16"></div>
              </div>
            </div>
            {% if page.language == 'en' %}
              <p>If you use <b>Responsive Design</b> because of <b>Media Queries</b> we support <b>Internet Explorer 9 and +</b> versions.</p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p><b>Responsive Design</b> olarak kodlama yapıyorsak <b>Media Queries</b> kullanımından kaynaklı <b>Internet Explorer 9 ve üzeri</b> versiyonları destekliyoruz.</p>
            {% endif %}
            <div class="dn-height-8"></div>
            {% if page.language == 'en' %}
              <p>If you use <b>Flexbox</b> we support <b>Internet Explorer 10 and +</b> versions.</p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p><b>Flexbox</b> özelliğini kullanıyorsak <b>Internet Explorer 10 ve üzeri</b> versiyonları destekliyoruz.</p>
            {% endif %}
            <div class="dn-height-8"></div>
            {% if page.language == 'en' %}
              <p>Other than the two exceptions above we supprt all the major desktop and mobile browsers.</p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p>Yukarıdaki iki durum dışında tüm masaüstü ve mobil browserlara destek verilmektedir.</p>
            {% endif %}
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
