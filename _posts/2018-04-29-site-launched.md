---
layout: post
title: "Launches Site"
date: "2018-04-29"
---

Well... not much to say yet.


{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
