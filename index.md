<strong>
http://www.orocos.org/ was down since mid August. Unfortunately we have not found a quick and easy way to fix it. It is planned to create a new website and also restore the contents of the Wiki that are still up-to-date. If you have questions, comments or want to contribute to this temporary page, please open an issue or pull request at https://github.com/orocos/orocos.org/issues.
</strong>

<i>
Most of the manuals linked below should probably be rewritten in [Markdown](https://guides.github.com/features/mastering-markdown/)
to be rendered by [Jekyll](https://jekyllrb.com/).
Contributions are welcome!
</i>

## Download

### Binaries

Binary builds are currently only available for Linux through [ROS](https://www.ros.org/).

* [ROS Installation instructions](http://wiki.ros.org/ROS/Installation)

### Source repositories

* The [Orocos Toolchain](https://github.com/orocos-toolchain/orocos_toolchain), consisting of...
  * [Orocos Real-Time Toolkit (RTT)](https://github.com/orocos-toolchain/rtt)
  * [Orocos Component Library (OCL)](https://github.com/orocos-toolchain/ocl)
  * [OroGen](https://github.com/orocos-toolchain/orogen)
  * ... and some of their dependencies.
* [Orocos Kinematics and Dynamics Library (KDL)](https://github.com/orocos/orocos_kinematics_dynamics)
* [Orocos Bayesian Filtering Library (BFL)](https://github.com/toeklk/orocos-bayesian-filtering)

For [ROS](https://www.ros.org/) users:

* [RTT ROS Integration](https://github.com/orocos/rtt_ros_integration)

## Documentation

### Latest released version ({{ site.data.releases[0].version }})

* [RTT API Reference](rtt/{{ site.data.releases[0].doc_branch }}/api/html/index.html)
* [OCL API Reference](ocl/{{ site.data.releases[0].doc_branch }}/api/html/index.html)

### Latest development version (master)

* [RTT API Reference](rtt/master/api/html/index.html)
* [OCL API Reference](ocl/master/api/html/index.html)

## Cheat sheets

* [OROCOS Cheat Sheet](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos_cheat_sheet.pdf)
* [RTT Cheat Sheet](rtt/{{ site.data.releases[0].doc_branch }}/xml/rtt_cheat_sheet.pdf)

## All manuals

* [Installing the RTT](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-installation.html) ([pdf](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-installation.pdf))
* [Component Builder's Manual](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-components-manual.html) ([pdf](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-components-manual.pdf))
* [Building Components using oroGen](http://rock-robotics.org/documentation/orogen)
* [Orocos plugins](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-rtt-plugins.html) ([pdf](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-rtt-plugins.pdf))
* [Orocos typekits](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-typekit-plugin.html) ([pdf](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-typekit-plugin.pdf))
* [Building Typekits using typegen](http://rock-robotics.org/documentation/orogen/type_definitions.html)
* [Orocos TaskBrowser](ocl/{{ site.data.releases[0].doc_branch }}/xml/orocos-taskbrowser.html) ([pdf](ocl/{{ site.data.releases[0].doc_branch }}/xml/orocos-taskbrowser.pdf))
* [Orocos Deployment](ocl/{{ site.data.releases[0].doc_branch }}/xml/orocos-deployment.html) ([pdf](ocl/{{ site.data.releases[0].doc_branch }}/xml/orocos-deployment.pdf))
* [Orocos Reporting](ocl/{{ site.data.releases[0].doc_branch }}/xml/orocos-reporting.html) ([pdf](ocl/{{ site.data.releases[0].doc_branch }}/xml/orocos-reporting.pdf))
* [Orocos CORBA Transport](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-transports-corba.html) ([pdf](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-transports-corba.pdf))
* [Orocos Message Queue Transport](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-transports-mqueue.html) ([pdf](rtt/{{ site.data.releases[0].doc_branch }}/xml/orocos-transports-mqueue.pdf))
* [The RTT-Lua Cookbook](http://www.orocos.org/wiki/orocos/toolchain/LuaCookbook)

## What is the Orocos Toolchain?

The Orocos Toolchain is your primary tool to create **real-time** robotics applications using modular, run-time configurable software components.

It provides:

* Multi-platform support: **Linux**, **Windows** (Visual Studio) and **Mac OS X**
* Extensions to other robotics frameworks: **ROS**, **Rock**, **Yarp**
* Code generators to transfer **user-defined data** between distributed components
* Run-time & real-time **configurable** and **scriptable** components
* **Logging** and **reporting** of system events and communicated data

It consists of:

* [AutoProj](http://www.rock-robotics.org/autoproj/), A tool to download and compile the necessary libraries (optional)
* The [Real-Time Toolkit](http://www.orocos.org/rtt), a component framework that allows us to write real-time components in C++
* The [Orocos Component Library](http://www.orocos.org/ocl), the necessary components to start an application and interact with it at run-time
* [OroGen](http://www.rock-robotics.org/documentation/orogen/) and [TypeGen](http://www.rock-robotics.org/documentation/orogen/),
  tools to generate ready-to-compile-and-run code from existing headers or component description files

Components built by users of Orocos are hosted in their own repositories.

