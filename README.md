# Tagly ( [demo](http://tagly.azurewebsites.net/) )
Issue tracker for a DMS web application, currently in private beta. ( DMS = Document Management System)

## Features 

 - **easy UI**, Reddit / HN like interface;
 - **tags**, label a post with multiple tags, so you can find it later;
 - **personal menu**, menu can be customized according to your login;
 - **search**, Search can contain tags and text, Eg. [machine-learning] tensorflow;
 - **combined tag search**, search can happen between multiple tags Eg. [course] [machine-learning] to find all posts labeled with *machine-learning* and *course*;
 - **functionality tags**, A tag can contain custom input elemens, eg. when adding a tag: *client-work*. It is possible to define 2 extra input fields: *Client Name:Text*, *Description:TextArea* and a  *chronometer* . You can also have HTML and much more. These tags CAN be hidden from the overview to avoid clutter;
 - **tag inheritance**, it is possible to inherit a tag, reducing tag clutter. Eg. Cloud-Platform > Azure -> Azure-VM . Cloud-Platform > Google-Cloud-Platform, Cloud > AWS > SES;
 - **multiple domains**, one instance can be spanned over multiple domains with different contents; 

## TODO
 - **payment Options**, Unique content can be added to a paywall. On tag and post basis. Donations are also possible;
 - **course navigation**, navigate through multiple posts from an author. On a domain basis or defined by the submitted;
 - **url manipulation**, you can add a affliate url for amazon urls. Override it by default or only when it's absent;
 - **API for auto-submit**, eg. reading in newsletters;
 - **RSS subscription**, tags can be subscribed through RSS;

Demo available on:  http://tagly.azurewebsites.net/

![Interface screenshot](/tagly-screenshot.png)
