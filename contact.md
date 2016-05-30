---
layout: page
title: Contact
permalink: /contact/
---
  <div class="wrapper">

    <div class="footer-col-wrapper row">
    <div class="col-xs-1"></div>
      <div>
        <ul class="col-xs-3" >
            <li><a href="mailto:{{ site.email }}">{{ site.email }}</a></li>
        </ul>
      </div>

        <div class="footer-col  footer-col-2">
            <ul class=" social-media-list col-xs-3">

                {% if site.github_username %}
                <li>
                Github: 
                    <a href="https://github.com/{{ site.github_username }}">{{ site.github_username }}</a>
                </li>
                {% endif %}
            </ul>
             <ul class=" social-media-list col-xs-3">
                {% if site.twitter_username %}
                <li>
                    Twitter: 
                    <a href="https://twitter.com/{{ site.twitter_username }}">
                    <span class="username">{{ site.twitter_username }}</span>
                    </a>
                </li>
                {% endif %}
            </ul>
        </div>
        <div class="col-xs-1"></div>
    </div>
        
    <div class="row">
        <div class="col-xs-1"></div>
            <div class="footer-col  col-xs-10">
                <p class="text">{{ site.description }}</p>
            </div>
        </div>
  </div>