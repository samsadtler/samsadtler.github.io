---
layout: page
title: Contact
permalink: /contact/
---
<div class="wrapper">

    <div class="row">
    
      <div >
            <form class="form-group" action="https://formspree.io/{{ site.email }}"
                  method="POST">
                  <!-- <div class="col-md-2"></div> -->
                  <ul class="col-md-12">
                        <li>
                                <input class="form-control" type="text" name="name" placeholder="Your Name">
      
                        </li>
                        <li>
                                <input class="form-control" type="email" name="_replyto" placeholder="Your Email"> 
                 
                        </li>
                        <li>
                                 <textarea class="form-control" name="message" placeholder="Your message"></textarea>
                        </li>
                        <li>
                                <input class="form-control" type="submit" value="Send">
                         
                        </li>
                  </ul>     
            </form>
            <div class="col-md-2"></div>
            <div class=" col-md-8 social-media-list">

                {% if site.github_username %}
        
                    <a href="https://github.com/{{ site.github_username }}">
                        <img src="../img/github.png">
                    </a>
              
                {% endif %}
                {% if site.twitter_username %}
                
                    <a href="https://twitter.com/{{ site.twitter_username }}">
                        <img src="../img/twitter.png" width="58px">

                    </a>
            
                {% endif %}
            </div>
        <!-- <div class="col-md-1"></div> -->
    </div>
        
</div>