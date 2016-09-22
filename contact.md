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
                  <div class="col-md-2"></div>
                  <ul class="col-md-8">
                        <li>
                            <div class="col-md-8">
                                <input class="form-control" type="text" name="name" placeholder="Your Name">
                            </div>
                        </li>
                        <li>
                            <div class="col-md-8">
                                <input class="form-control" type="email" name="_replyto" placeholder="Your Email"> 
                            </div>  
                        </li>
                        <li>
                             <div class="col-md-8">
                                 <textarea class="form-control" name="message" placeholder="Your message"></textarea>
                            </div>
                        </li>
                        <li>
                             <div class="col-md-8">
                                <input class="form-control" type="submit" value="Send">
                            </div>
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
                        <img src="../img/twitter.png">

                    </a>
            
                {% endif %}
            </div>
        <!-- <div class="col-md-1"></div> -->
    </div>
        
</div>