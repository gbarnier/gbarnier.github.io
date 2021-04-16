---
layout: ml
title: Machine Learning Projects
tag: ML projects
share: true
permalink: /ml_projects/
---
<style>

.icon-fig{
    width: 250px;
    height: 200px;
    }
.description-text{
    width: 220px;
    text-align:left;
    margin-bottom: -0.5em;
    color: black;
    font-size: 18px;
}
.paragraph{
    text-align:justify;
    font-size: 18px;
    margin-bottom: 1.0em;
    width: 800px;
}    

@media screen and (max-width: 1500px) {
    .icon-fig{
        width: 150px;
        height: 120px;
        }
    .description-text{
        width: 150px;
        text-align:left;
        margin-bottom: -0.5em;
        color: black;
        font-size: 18px;
    }            
    .paragraph{
        text-align:justify;
        font-size: 18px;
        margin-bottom: 0.5em;
        width: 400px;
    }
}
</style>

<body style="background-color: #F2F3F4; ">
    <br>    
    <div class="tiles">                                                             
        {% for post in site.categories.ml_projects %}
            {% include post-grid.html %}                                                  
        {% endfor %}                                                                    
    </div>
</body>
