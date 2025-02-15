---
title: "Grouping"
description: "Group entities within Dynatrace console."
lead: "Group entities within Dynatrace console."
date: 2021-04-05T11:45:00+12:00
lastmod: 2021-04-05T11:45:00+12:00
draft: false
images: []
menu: 
  dynatrace:
    parent: "doc-guide"
weight: 210
toc: true
---

## Entity level grouping

### Host

  1. [Host Groups](https://www.dynatrace.com/support/help/shortlink/host-groups)

     Defined during OneAgent install. Can update post install using oneagentctl.

  
  2. [Tags](/dynatrace/docguide/grouping/#based-on-tags-and-metadata)

### Process
  
  1. [Process group detection](https://www.dynatrace.com/support/help/shortlink/process-groups#process-group-detection-rules-based-on-process-properties)
                
    Settings > Processes and containers > Process group detection
            
  2. [Tags](/dynatrace/docguide/grouping/#based-on-tags-and-metadata)
        
### Services
    
  1. [Merged services](https://www.dynatrace.com/support/help/shortlink/merged-services)
            
    Settings > Server-side service monitoring > Merged service monitoring > Create merged service
    
  2. [Tags](/dynatrace/docguide/grouping/#based-on-tags-and-metadata)
    
## Based on Tags and metadata

> [doc](https://www.dynatrace.com/support/help/shortlink/tags-and-metadata-hub)
        
[How to define tags](https://www.dynatrace.com/support/help/shortlink/tagging)
  
[Best practices and recommendations for tagging](https://www.dynatrace.com/support/help/shortlink/tagging-best-practices)
  
### Manually applied tags

> [doc](https://www.dynatrace.com/support/help/shortlink/tagging#manual-approach)
  
    Settings > Tags > Manually appled tags > Add Tag
    
  Auto-complete is available for existing manual tags.
      
    Host, Process/Process Group, Service, Database etc > {Open entity}> Properties/Properties and tags > + Add tag
    
### Automatically applied tags

> [doc](https://www.dynatrace.com/support/help/shortlink/tagging#automated-approach)

Auto-tag entities based on rules.

    Settings > Tags > Automatically applied tags > Create Tag

## Management Zones

> [doc](https://www.dynatrace.com/support/help/shortlink/management-zones-hub)

Management Zones can be thought of as workspaces with the console. Management Zone allows filtering of environment specific team entities.

    Settings > Preferences > Management zones > Add new management zone