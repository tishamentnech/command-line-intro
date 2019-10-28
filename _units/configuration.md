---
layout: page
title: Configuration

order: 2
duration: 10
tutorial: true
instructors_notes: true
description: |
  This workshop is targeted to using a Unix shell. If participants are using a Windows machine they will need to install a Unix Shell of some kind.
instructors_note: |
  If participants are using Windows they will need to install a interface. Windows 10 allows for a Unix Shell to be installed. Git for Windows is an option. There is also a Bash shell command line tool for windows. Windows users can also install a Unix/Linux emulator. 


```ruby
 ThisObject.function param
```

Jekyll websites always use a `_config.yml` file to keep site wide settings such 
as **title** or **description**. The values set here are available from
from within your markdown or html using ` {{ site.setting_name }}`. You
will see and use this often as you work. You can also add your own
settings as needed.

The `_config.yml` is commented with more detailed instructions. To get started
we'll just change the most important ones. Make the changes below.

```yml

    title: Introduction to Command Line
    
    description: Learn how to navigate your computer and manipulate files using the command line interface. 
    
    # Multiple authors go on the same line, just format how you like.
    # Same with companyies
    author:
      name: Tisha Mentnech & Mira Waller
      # url:  http://example.com/
      company:
          name: NC State University
          # url:  http://example.com/
    
    # Any value is ok, Beginner|Intermediate|Advanced are recommended, required 
    level: Beginner
    
    # This needs to be set to your repository name, or it won't work on GitHub.
    # If you are deploying elsewhere it may not be necessary.
    # It is overridden if you are working locally when you start the server
    baseurl: "/command-line-intro"
```
    












