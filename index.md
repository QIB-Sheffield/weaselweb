---
layout: home
title: Den
nav_order: 1
description: "Prototyping medical imaging processing."
permalink: /
---
# What is Weasel? 

**!!! UNDER DEVELOPMENT !!!**

**Weasel is a Python environment for developing and deploying quantitative medical imaging applications.** 

`weasel` aims to simplify the process of testing prototype image processing pipelines on clinical data, by avoiding the need for dedicated graphical interface development and removing the overhead involved in interfacing with DICOM databases. 

This will speed up the translation of new methods into early stage clinical studies, bringing forward the point where prototypes can be stress-tested under real world conditions. 

![](/media/Challenge.jpg)

# Who can use Weasel?

`weasel` is for you if:

**You are developing methods for processing of medical images, and you want to test these on clinical data, to visualise the results, or to integrate them in clinical studies.**

`weasel` will offer you an easy way to create an application by wrapping your algorithms into a platform which integrates seamlessly with DICOM databases (read and write), and includes graphical interfaces for visualising multi-dimensional imaging data, defining regions of interest, or extracting quantitative data. 

If you want to share your methods with the wider community, you can integrate `weasel` apps into the distribution of your code, allowing clinical users to run your methods on their clinical data through the built-in graphical interface. 

**You run clinical studies involving medical imaging and are looking to integrate quantitative endpoints that are not available as commercial tools or as plugins for standard DICOM image viewers.**

`weasel` provides your collaborators that develop new methods and easy way to package them up in a `weasel` app for use by an image analyst or clinical user through a graphical interface including a basic DICOM viewer. 

Alternatively, you can browse the `weasel` pipeline library and customize a `weasel` app to fit the needs of your study. This will also promote reproducible science by providing a means for others to verify your results independently.

# How does Weasel work?

If you are a method developer, and you have a package with some new image processing algorithm writting in Python, then you can wrap these methods up into a `weasel` app in 3 easy steps. You can then distribute the `weasel` app along with your code so others can apply your methods on their DICOM data directly through the `weasel` DICOM viewer. `weasel` is available under a permissive Apache 2.0 license, allowing you to distribute the app on your own terms.

![](/media/Approach.png)

You can wrap your Python prototype code into `weasel` in 3 easy steps:

**[1] Script:** Use `weasel`'s intuitive, built-in scripting language to create a `weasel` pipeline that can you maintain locally or post to the `weasel` pipeline library to share with others.

**[2] Build:** Use `weasel`'s builder module to assemble your pipelines along with any others you may find in the `weasel` pipeline library into a `weasel` configuration. If you are testing the method as part of an ongoing development - you can stop here. Run the configuration from source to apply your code to DICOM data, visualise the results, extract data etc.

**[3] Compile:** Use `weasel`'s compiler to created an app that allows you to distribute your `weasel` configuration as a single file, and will allow others to run it and apply your methods by simply downloading and running the app. Weasel has a permissive license meaning you can distribute these apps as part of your package.

# How do I get started?

Whether you are a clinical user or a developer, the best way to familarise yourself with `weasel` is to follow these three steps:

**[1] Play with apps:** Download the demo app from the app store, open up some DICOM data, and try out some of the visualisation and analysis. Detailed instructions and tutorials are provided [here](https://qib-sheffield.github.io/weaselweb/wrappers.html)

**[2] Build your own:** Next you can try building some different `weasel` configurations by assembling pipelines from the library using the configuration builder. Detailed instructions and examples are provided [here](https://qib-sheffield.github.io/weaselweb/configurations.html).

**[3] Script a pipeline:** Finally, you can try using `weasel` scripting to wrap one of your own functions up into a `weasel` pipeline and add it your configuration. Detailed instructions and tutorials with simple examples are provided [here](https://qib-sheffield.github.io/weaselweb/pipelines.html).
