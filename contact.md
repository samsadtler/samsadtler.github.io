---
layout: page
title: Contact
permalink: /contact/
---
  <div class="wrapper">

    <div class="row">
    <div class="col-md-1"></div>
      <div>
        <ul class="col-md-3" >
            <li><a href="mailto:{{ site.email }}">{{ site.email }}</a></li>
        </ul>
     
            <ul class=" social-media-list col-md-3">

                {% if site.github_username %}
                <li>
                <h4>Github: </h4>
                    <a href="https://github.com/{{ site.github_username }}">{{ site.github_username }}</a>
                </li>
                {% endif %}
            </ul>
             <ul class=" social-media-list col-md-3">
                {% if site.twitter_username %}
                <li>
                    <h4>Twitter: </h4>
                    <a href="https://twitter.com/{{ site.twitter_username }}">
                    <span class="username">{{ site.twitter_username }}</span>
                    </a>
                </li>
                {% endif %}
            </ul>
        <div class="col-md-1"></div>
    </div>
        
    <div class="row">
        <div class="col-md-1"></div>
            <div class="col-md-10">
                <p class="text">{{ site.description }}</p>
            </div>
        </div>
  </div>