---
title: Easy Trips
tags: [getting_started]
sidebar: false
type: homepage
toc: false

---

### Field Trip Software Kept Simple


<!-- Highlights -->
<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">Highlights</h2>
    </div>
    <div class="col-lg-12">

        {% assign features = site.features | sort: 'order' | where: 'featured', 'true' %}
        {% for feature in features %}
        <div class="col-md-3 col-sm-6">
            <div class="panel panel-default text-center">
                <div class="panel-heading">
                    <span class="fa-stack fa-5x">
                        <i class="fa fa-circle fa-stack-2x text-primary"></i>
                        <i class="fa fa-{{ feature.icon }} fa-stack-1x fa-inverse"></i>
                    </span>
                </div>
                <div class="panel-body">
                    <h4>{{ feature.benefit }}</h4>
                    <p>{{ feature.summary }}</p>
                    <a href="{{ feature.url }} " class="btn btn-primary">Learn More</a>
                </div>
            </div>
        </div>
        {% endfor %}
    </div>
</div>

<!-- Service Tabs -->
<!--
<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">Service Tabs</h2>
    </div>
    <div class="col-lg-12">

        <ul id="myTab" class="nav nav-tabs nav-justified">
            <li class="active"><a href="#simple" data-toggle="tab"><i class="fa fa-tree"></i> Simple</a>
            </li>
            <li class=""><a href="#secure" data-toggle="tab"><i class="fa fa-lock"></i> Secure</a>
            </li>
            <li class=""><a href="#support" data-toggle="tab"><i class="fa fa-phone"></i> Support</a>
            </li>
            <li class=""><a href="#start" data-toggle="tab"><i class="fa fa-car"></i> Start Today</a>
            </li>
        </ul>

        <div id="myTabContent" class="tab-content">
            <div class="tab-pane fade active in" id="simple">
                <h4>Simple</h4>
                <p>Every effort has been made to keep Easy Trips as simple as possible while still providing a full field trip application program.  This goal is what inspired the name, and we take all feedback on how to improve it very seriously.  </p>
                <p>In fact, we want to make it the best for you, providing feedback is always just one click away</p>
                <TODO>picture of feedback icon inside app</TODO>
            </div>
            <div class="tab-pane fade" id="secure">
                <h4>Secure</h4>
                <p>Security was incorporated into the design of Easy Trips from day one.  With a strong background in consulting and developing applications to meet both Washington State and HIPAA data security standards, you can trust that we have your best interests in mind.</p>
                <p>
                <a href="{{site.data.urls.mydoc_iterm_profiles.link}}">Read more about security.</a>
                </p>
            </div>
            <div class="tab-pane fade" id="support">
                <h4>Support</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quae repudiandae fugiat illo cupiditate excepturi esse officiis consectetur, laudantium qui voluptatem. Ad necessitatibus velit, accusantium expedita debitis impedit rerum totam id. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Natus quibusdam recusandae illum, nesciunt, architecto, saepe facere, voluptas eum incidunt dolores magni itaque autem neque velit in. At quia quaerat asperiores.</p>
                <p>...</p>
            <div class="tab-pane fade" id="start">
                <h4>Start Today</h4>
                <p>...</p>
            </div>
        </div>

    </div>
</div>
-->


<!-- Highlights -->
<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">Reasons to use Easy Trips</h2>
    </div>
    <div class="col-lg-12">

        {% assign features = site.features | sort: 'order' %}
        {% for feature in features %}
        <div class="col-lg-6">
        <div class="media">
            <div class="pull-left">
                <span class="fa-stack fa-2x">
                      <i class="fa fa-circle fa-stack-2x text-primary"></i>
                      <i class="fa fa-{{ feature.icon }} fa-stack-1x fa-inverse"></i>
                </span>
            </div>
            <div class="media-body">
                <h4 class="media-heading">{{ feature.benefit }}</h4>
                <p>{{ feature.summary }}</p>
                <a href="{{ feature.url }} " class="btn btn-primary">Learn More</a>
            </div>
        </div>
        </div>
        {% endfor %}
    </div>
    
</div>



