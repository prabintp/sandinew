---
title: about
section_id: about
about_desc:
- item: we want to tell your wedding story through compelling images that will blow
    your mind. We don't want to just give you photos, we want to give you works of
    art that transcend wedding photography, that communicates the essence of who you
    are, that tell stories beyond what you see...
skills:
- title: Candid & portrait photogrphy
  percent: 100
- title: Traditional wedding  photography
  percent: 100
- title: Albums and Framing
  percent: 100
- title: Branding and cenimatography
  percent: 100
members:
- name: Mark Wayne
  position: founder
  desc: consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet
    dolore magna aliquam erat volutpat consectetuer sit.
  avatar: images/@stock/member-1.jpg
  socials:
  - icon_class: fa fa-twitter
    url: http://twitter.com
  - icon_class: fa fa-facebook
    url: http://facebook.com
- name: Kate Holms
  position: Creative Director
  desc: consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet
    dolore magna aliquam erat volutpat consectetuer sit.
  avatar: images/@stock/member-2.jpg
  socials:
  - icon_class: fa fa-twitter
    url: http://twitter.com
  - icon_class: fa fa-facebook
    url: http://facebook.com
  - icon_class: fa fa-dribbble
    url: http://dribbble.com
- name: Tom Hason
  position: Designer
  desc: consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet
    dolore magna aliquam erat volutpat consectetuer sit.
  avatar: images/@stock/member-3.jpg
  socials:
  - icon_class: fa fa-twitter
    url: http://twitter.com
  - icon_class: fa fa-facebook
    url: http://facebook.com
  - icon_class: fa fa-tumblr
    url: http://tumblr.com
- name: Lily Whrem
  position: Developer
  desc: consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet
    dolore magna aliquam erat volutpat consectetuer sit.
  avatar: images/@stock/member-4.jpg
  socials:
  - icon_class: fa fa-twitter
    url: http://twitter.com
  - icon_class: fa fa-facebook
    url: http://facebook.com
clients:
- images/@stock/client-grey-1.png
- images/@stock/client-grey-2.png
- images/@stock/client-grey-3.png
- images/@stock/client-grey-4.png
- images/@stock/client-grey-5.png
- images/@stock/client-grey-6.png
layout: default
---

<div class='full' style='background: #333'>
  <div class='row'>
    <div class='large-12 columns'>
      <h2 style='color: #fff;'>About the team</h2>
    </div>
  </div>
  <div class='two spacing'></div>
</div>
<div class='full'>
  <div class='row'>
    <div class='large-12 columns'>
      <h3>what We are</h3>
      <div class='spacing'></div>
      {% for desc in page.about_desc %}
         <p>{{desc.item}}</p>
       {% endfor %}
      <p>Shooting weddings with a little twist of Fashion and drama gives a couple something unique to cherish</p>
      <div class='two spacing'></div>
    </div>
   <!-- <div class='large-6 columns'>
      <h3>We Provide</h3>
      <div class='spacing'></div>
      <div class='mod modBarGraph'>
        <ul class='bars'>
          {% for skill in page.skills %}
            <li>
              <h4 style=''>
                
                <strong>{{skill.percent}}%</strong>
              </h4>
              <p class='highlighted' data-percent='{{skill.percent}}'>{{skill.title}}</p>
            </li>
          {% endfor %}
        </ul>
      </div>
    </div>
  </div>
</div> -->
<div class='two spacing'></div>
<!--<div class='full' style='background: #f5f5f5'>
  <div class='row'>
    <div class='large-12 columns'>
      <h3>The team</h3>
      <div class='spacing'></div>
    </div>
  </div>
  <div class='row'>
    {% for member in page.members %}
      <div class='small-6 medium-3 large-3 columns'>
        <div class='mod modTeamMember style-2'>
          <div class='member'>
            <img class="avatar" alt="" src="{{site.url}}/{{member.avatar}}" />
            <div class='overlay'>
              <ul class='socials'>
                {% for social in member.socials %}
                  <li>
                    <a href='{{social.url}}'>
                      <i class='{{social.icon_class}}'></i>
                    </a>
                  </li>
                {% endfor %}
              </ul>
            </div>
          </div>
          <h3>{{member.name}}</h3>
          <p class='position'>{{member.position}}</p>
          <p>{{member.desc}}</p>
          <div class='two spacing'></div>
        </div>
      </div>
    {% endfor %}
  </div>
  <div class='two spacing'></div>
</div>
 <div class='full'>
  <div class='row'>
    <div class='large-12 columns'>
      <h3>Our clients</h3>
      <div class='spacing'></div>
      <div class='mod modClients' data-slides_to_show='5'>
        <div class='clients'>
          {% for client in page.clients %}
            <div><img alt="" src="{{client}}" /></div>
          {% endfor %}
        </div>
      </div>
    </div>
  </div>
  <div class='four spacing'></div>
</div> -->
