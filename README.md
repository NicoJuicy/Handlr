# Tagly ( [demo](http://tagly.azurewebsites.net/) )
Issue tracker for a DMS web application, currently in private beta. ( DMS = Document Management System)

## Features 

 - **easy UI**, Reddit / HN like interface;
 - **Tags**, label a post with multiple tags, so you can find it later;
 - **Dynamic menu**, menu can be customized according to your login;
 - **Search**, Search can contain tags and text, Eg. [machine-learning] tensorflow;
 - **Combined tag search**, search can happen between multiple tags Eg. [course] [machine-learning] to find all posts labeled with *machine-learning* and *course*;
 - **Functionality tags**, A tag can contain custom input elemens, eg. when adding a tag: client-work. It is possible to define 2 extra input fields: Client Name, Description:TextArea and a  chronometer. So the time can be measured, a description added  and a client name as extra info. You can also have HTML and much more. These tags CAN be hidden from the overview;
 - **Tag inheritance**, it is possible to inherit a tag, reducing tag clutter. Eg. Cloud-Platform > Azure -> Azure-VM . Cloud-Platform > Google-Cloud-Platform, Cloud > AWS > SES;
 - **Multiple domains**, one instance can be spanned over multiple domains with different contents; 

## TODO
 - **Payment Options**, Unique content can be added to a paywall. On tag and post basis. Donations are also possible;
 - **Course navigation**, navigate through multiple posts from an author. On a domain basis or defined by the submitted;
 - **Url manipulation**, you can add a affliate url for amazon urls. Override it by default or only when it's absent;
 - **API for auto-submit**, eg. reading in newsletters;
 - **RSS subscription**, tags can be subscribed through RSS;

Demo available on:  http://tagly.azurewebsites.net/

![Interface screenshot](/tagly-screenshot.png)
