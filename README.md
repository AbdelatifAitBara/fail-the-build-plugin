# Features

-   Set or change the status of a build  
-   This plugin is provided to help test the behaviour of your Jenkins configuration.  
-   Use this plugin to test notifiers, publishers, promotions, build pipelines...

You can only make the build result worse than it is at the point the build step runs!

# Compatibility

This plugin is compatible with any version of **Jenkins** (1.396+)

# Install

Install from the Plugin Manager (Manage Jenkins \> Manage Plugins) under
"Build Tools".

To install manually, download the latest plugin from
<http://mirrors.jenkins-ci.org/plugins/fail-the-build-plugin/> and use
the Upload Plugin option in the Advanced tab of the Plugin Manager.

# Configure

Add the build step, by clicking "Add build step" and selecting "Set the
build result"

![](Docs/images/Configure.png)

###### Result

Select the status that you want. Options are Success, Unstable, Failed,
Aborted, and Cycle.

Selecting Cycle will cause the result to cycle based on the build
number. Image of Build history with Cycle selected below.

![](Docs/images/BuildHistory.png)

##### Advanced options

Click the Advanced button to enable the results to be set for specific
build numbers.

![](Docs/images/AdvancedOptions.png)

###### Success, Unstable, Failed, Aborted

For each result, a list of build numbers for which it should be set
instead of the value in the Result drop down.