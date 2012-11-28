---
layout: post
title: "Start a Blog on AppHarbor in 5 Minutes"
description: ""
category: 
tags: [.NET, nScanty]
---
{% include JB/setup %}

Today I'm making my minimalist ASP.NET MVC 3 blog available on GitHub. You can have a blog up and running on [AppHarbor](https://appharbor.com/) in moments, with no coding required.  

First, fork the project on [GitHub](https://github.com/tltjr/nScanty).  

In order to login to your blog once deployed, you will need to change the user name and password in the Web.config appSettings. This can be done directly through GitHub, or you can clone your fork of the project and make the updates. nScanty also supports a hashed password in the config file if you would prefer not to store your password as plain text (encouraged). This is covered in greater detail in the [README](https://github.com/tltjr/nScanty).  

While you are making updates to the config, go ahead and change the title, description and author as well.  

Next, create an account on [AppHarbor](https://appharbor.com/) if you don't have one already and create a new application (name it whatever you like).  

AppHarbor should now offer the option to "Configure GitHub to deploy to AppHarbor" in the "Getting Started" section as shown below:  

![Getting Started](/img/2-config-github-apphb.png)  

Follow this link and select "nScanty" as the application from the dropdown on the next page.  

Finally, in the AppHarbor add-ons section, enable the MongoLab add-on.  

Your dashboard should look similar to this:  

![Dashboard](/img/5-dashboard-apphb.png)  

In the upper-right hand corner of the image, you'll see a link to go to your application. Go ahead and click the link and you should be directed to login and begin creating posts (see below).

![Start Screen](/img/start-page.png)


There is additional information in the README file on [GitHub](https://github.com/tltjr/nScanty).  

Please feel free to send me pull requests if you make any useful updates.

