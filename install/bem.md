---
layout: flexiblegs
title: bem
permalink: /install/bem/
---

<div class="dn-browser">
  <div class="dn-browser-header">
    <div class="dn-style--title"><span>bem</span></div>
    {% include flexiblegs/logo.html %}
  </div>
  <div class="dn-browser-body">
    <div class="dn-browser-body__pre">
      <div class="wrap xl-table xl-gutter-40 xl-top xl-center md-normal">
        <div class="col xl-width-360 md-1-1">
          {% include flexiblegs/social-media.html %}
        </div>
        <div class="col xl-1-1">
          <div class="dn-content">
            {% if page.language == 'en' %}
              <a href="https://raw.githubusercontent.com/flexiblegs/flexiblegs-bem/master/flexiblegs-bem.css" download>Download the file</a> and add the project as follows.
            {% endif %}
            {% if page.language == 'tr' %}
              <a href="https://raw.githubusercontent.com/flexiblegs/flexiblegs-bem/master/flexiblegs-bem.css" download>Dosyayı indirin</a> ve aşağıdaki gibi projenize ekleyin.
            {% endif %}
          </div>
          <div class="dn-height-16"></div>
          <pre><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
            --><div class="comment">&lt;head&gt;<br/><!--
            -->&nbsp;&nbsp;&lt;link rel="stylesheet" href="<span>flexiblegs-bem.css</span>"&gt;<br/><!--
            -->&lt;/head&gt;</div><!--
          --></pre>
          <div class="dn-height-40"></div>
          <div class="dn-content">
            <a href="https://www.npmjs.com/package/flexiblegs-bem">npm</a>
          </div>
          <div class="dn-height-16"></div>
          <pre><div class="dn-tag dn-tag--gray dn-tag--bottom">terminal</div><!--
            --><div class="comment">$ npm install --save <span>flexiblegs-bem</span></div><!--
          --></pre>
          <div class="dn-height-40"></div>
          <div class="dn-content">
            <a href="http://bower.io/search/?q=flexiblegs-bem">bower</a>
          </div>
          <div class="dn-height-16"></div>
          <pre><div class="dn-tag dn-tag--gray dn-tag--bottom">terminal</div><!--
            --><div class="comment">$ bower install --save <span>flexiblegs-bem</span></div><!--
          --></pre>
        </div>
      </div>
    </div>
    <div class="dn-height-40"></div>
    <div class="dn-browser-footer">
      <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
        <div class="col">
          <a href="https://github.com/flexiblegs/flexiblegs-bem" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-bem</a>
        </div>
      </div>
    </div>
  </div>
</div>
