# Handlr ( [demo](http://handlr.sapico.me/) ) 
### -- renamed from tagly
Issue tracker for a DMS web application, currently in private beta. ( DMS = Document Management System). It's based on Reddit, Hackernews with more advanced functionality

## Features 

 - **easy UI**, Reddit / HN like interface;
 - **voting**, vote on good stories. See your post go trending;
 - **tags**, label a post with multiple tags, so you can find it later;
 - **actions**, a tag can contain actions. ( see [#92](https://github.com/NicoJuicy/Tagly/issues/92) );
 - **personal menu**, menu can be customized according to your login, you can auto-include tags when users register ( they can always remove it);
 - **personal view**, only view the content that you voted on;
 - **search**, Search can contain tags and text, Eg. [machine-learning] tensorflow;
 - **combined tag search**, search can happen between multiple tags Eg. [course] [machine-learning] to find all posts labeled with *machine-learning* and *course*;
 - **functionality tags**, A tag can contain custom input elemens, eg. when adding a tag: *client-work*. It is possible to define 2 extra input fields: *Client Name:Text*, *Description:TextArea* and a  *chronometer* . You can also have HTML and much more. These tags CAN be hidden from the overview to avoid clutter;
 - **tag inheritance**, it is possible to inherit a tag, reducing tag clutter. Eg. Cloud-Platform > Azure -> Azure-VM . Cloud-Platform > Google-Cloud-Platform, Cloud > AWS > SES;
 - **tag synonyms**, better organise your tags by creating synonyms. One Tag declares the behaviour for all the synonyms
 - **multiple domains**, one instance can be spanned over multiple domains with different contents; 
 - **different roles**, admins have super powers, others could have less;
 - **role tags**, only certain user roles see certain tags;
  - **url manipulation**, you can add a affliate url for amazon urls. Override it by default or only when it's absent ( [#30](https://github.com/NicoJuicy/Tagly/issues/30));
 - **RSS subscription**, tags can be subscribed through RSS ( [#12](https://github.com/NicoJuicy/Tagly/issues/12) );
 - **RSS Feed import**, automaticly import items from a feed, add the feed tags or manually add tags to it;
 - **bookmarklet**, generate a new post by clicking on a link in your browser bookmarks ( adds title & url );
 
## TODO
 - **Sticky**, Make posts a stick in general overview or in a tag. Make it extra visible ( admins only) ( [#42](https://github.com/NicoJuicy/Tagly/issues/42) );
 - **payment options**, Unique content can be added to a paywall. On tag and post basis. Donations are also possible ( [#32](https://github.com/NicoJuicy/Tagly/issues/32) ) ;
 - **payout by commission**, to reward unique content authors ( [#41](https://github.com/NicoJuicy/Tagly/issues/41) );
 - **course navigation**, navigate through multiple posts from an author. On a domain basis or defined by the submitted ( [#33](https://github.com/NicoJuicy/Tagly/issues/33) );
 - **ghosting**, hide some users if they are annonying / irrelevant ( [#43](https://github.com/NicoJuicy/Tagly/issues/43));
 - **API for auto-submit**, eg. reading in newsletters;
 - **customize layout**, make the site suited to your organisation / mission;
 - **newsletter**, auto generate a newsletter based on the content you submitted [#51](https://github.com/NicoJuicy/Tagly/issues/51) [#52](https://github.com/NicoJuicy/Tagly/issues/52) 

Demo available on:  http://tagly.azurewebsites.net/

![Interface screenshot](/tagly-screenshot.png)

## Opensource projects, caused by Tagly's creation ;) :

 - https://github.com/NicoJuicy/SendyAPI.dotnet ( a dot net core client for Sendy )
 - https://github.com/NicoJuicy/WebsiteAsImageWebService ( a selfhosted nodejs service for generating thumnails from a website )
 -  https://github.com/NicoJuicy/WebsiteAsImageWebService.Api.Csharp/ ( API in c# dotnet core for grabbing the file )
