---
layout: page
title: Contact
permalink: /contact/
---
<div class="wrapper">

    <div class="row">
    <div class="col-md-4"></div>
      <div>
        <ul class="col-md-3" >
            <li><a href="mailto:{{ site.email }}">{{ site.email }}</a></li>
        </ul>
     
            <ul class=" social-media-list col-md-3">

                {% if site.github_username %}
                <li>
                    <a href="https://github.com/{{ site.github_username }}">
                        <img src="../img/github.png">
                    </a>
                </li>
                {% endif %}
            </ul>
             <ul class=" social-media-list col-md-3">
                {% if site.twitter_username %}
                <li>
                    <a href="https://twitter.com/{{ site.twitter_username }}">
                        <img src="../img/twitter.png">

                    </a>
                </li>
                {% endif %}
            </ul>
        <div class="col-md-1"></div>
    </div>
        
</div>