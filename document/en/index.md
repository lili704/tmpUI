# Overview

In short, `tmpUI` helps you combine scattered `html`, `js` and `css` to form a complete program.  

If you have developed a website based on a back-end template system (such as `PHP`) built in `MVC` mode before, then you can use `tmpUI` to build a similar website with basically no extra learning cost.

Programs written based on `tmpUI` don't need to be compiled, packaged, or manage version dependencies. Minimize your mental burden. Just put it directly into the browser and run it.  

We have examples for each feature to get you up and running quickly.   
Not surprisingly, you'll be done in a few hours.


# Contents
* Start
  * [project structure](./struct.md)
  * [application entry](./main.md)
  * [configuration parameters](./params.md)
* Core: modularity and routing
  * [static route](./route.md)
  * [resource group](./resource.md)
    * Pre- and post-resource groups
    * Other types of files supported by the resource group
    * Startup
  * [process resource path](./url.md)
    * Convert links to application paths
    * Convert correct paths for static resources
* Advanced
  * [Templates](./temp.md)
    * Implementing templates
    * Generate lists
  * [Multi-language support](./i18n.md)
    * Render on load
    * Rendering after loading
    * Real-time language replacement
    * Language files
    * Auto-detect language
  * [Dynamic-route](./route-dynamic.md)
  * [Dynamic-event-following-route](./route-dynamic-event.md)
  
# Case

If you have built a project using tmpUI, feel free to submit an issue and we will put it on display here.  
https://app.tmp.link A good web site to use.  
http://bs4.vx.link Bootstrap 4 Chinese documentation.  
https://www.vx.link Vx Link.   

# Thinking

In the old days, `PHP`, `ASP.net`, `Java` and `jQuery` ruled half of `Web` development. Now, only `PHP` and `Java` are left. The `MVC` paradigm was once the mainstream, and despite the changing times and the rise of mobile, there are still many ideas that have been passed down to this day.

From past experience, the authors believe that it is very important to not go with a certain framework (dependency) as much as possible as a basic strategy (this requires a considerable level of understanding and application of the programming language itself you are using, also known as programming fundamentals). In practice, however, it is not possible to implement every feature again by yourself (build the wheel), so there is a guideline here: the chosen wheel, which cannot limit the current functionality and cause constraints on future functionality. This is also known as low coupling.

Our ultimate goal is to make a good and useful product. It is common for a product to be tinkered with during the design and implementation process, so the guidelines mentioned above can help this product not be bound.

At the beginning of designing `tmp.link`, the author looked at `VUE` and `React`, frameworks designed for modern applications and with pretty good design patterns, and I thought I'd consider using them if I had a new project.  
But for our project, we can't take a big step and need to consider the time cost. Therefore, I designed `tmpUI`.  

So is there any `tmpUI` that breaks the above guideline (low coupling)?  

The author believes that there is not.  
The world of `Javascript` has a very large number of plugins that work very well and do not interfere with each other. This is really friendly for programmers who rely on these plugins for their functionality. Migrating your project from a template-structured back-end project to `tmpUI` doesn't require you to learn a whole new design pattern or even syntax.

The old `Javascript` plug-in now works too, which is another important goal we designed it for.  
The essence of `tmpUI` is actually similar to the relationship between `C++` and `C` in that it adds `include` or `require` functionality to the browser in such and such a way that projects previously based on `MVC` templates on the backend can migrate to a front- and back-end separation model at minimal cost. And developers don't have high learning costs. So you can also think of `tmpUI` as another form of `Javascript` plug-in.

At this stage, `tmpUI` implements the basic modularity and routing, but also adds additional advanced features: embedded templates, multi-language support, dynamic routing, and other three more useful features.

# Copyright

`tmpUI` is released under the `MIT License`.
You are free to use it in your own projects, modify it, copy it and distribute it, without restriction to commercial use.
Please retain the original copyright.
