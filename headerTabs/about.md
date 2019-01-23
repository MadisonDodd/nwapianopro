---
layout: page
title: About
permalink: /about
---


<div>
<h1>About Us</h1>
My name is Andrew Dodd, owner and proprietor of North West Arkansas Piano Pro LLC.
Coming from a family of 13 brothers and sisters we moved a lot, and I always helped in the moves. My father taught me a lot of moving techniques to not scratch or dent any furniture. I took this knowledge and came to North West Arkansas where I work fulltime doing Trim work for a Construction company. I use my free time to move Pianos as a part time business owner. 

    <div>
    {% for pageName in site.pages%}
        {%if pageName.title == "Inquiry"%}
            For a free inquiry about our prices and services click the link here-> 
            <a href="{{pageName.url}}">{{pageName.title}}</a>
        {%endif%}
    {%endfor%}
    </div>
</div>
