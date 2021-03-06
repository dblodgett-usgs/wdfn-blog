---
title: Improving Monitoring Pages with User Feedback
author: Candice Hopkins
date: '2021-01-12'
slug: ImprovingMonitoringPages
categories:
  - Software Development
  - water information
tags:
  - Water Data for the Nation
draft: False
type: post
description: Improvements to next-generation monitoring pages in response to user feedback
keywords: 
  - water data
  - water information
  - web page
  - monitoring data
author_staff: candice-hopkins
author_email: <chopkins@usgs.gov>
image: /static/ImprovingMonitoringPages/Gif.gif
---







User feedback is a vital part of our design process. We’ve asked users
to provide feedback on our
[next-gen](https://waterdata.usgs.gov/blog/wdfn-tng/) monitoring
location pages and they’ve submitted some great ideas! Here are some
things our users have asked for, and how we’ve responded to their
requests:

# Better map

Users asked us to improve the map in a few ways and we responded:

-   They requested a more detailed basemap, showing streets and
    landmarks. We swapped out the old basemap and replaced it with our
    very own [USGS National
    Map](https://www.usgs.gov/core-science-systems/national-geospatial-program/national-map).
    Users can now see details at the local level, including topography
    and local place names.

-   They asked us to show all monitoring locations in the field of view,
    not just other locations on the same stream. We now show all active
    monitoring locations nearby.

-   Another common request was to reduce the opacity of the upstream
    basin to make it easier to see features under the map layer. The
    upstream basin is now projected in a much lighter shade.



{{< figure src="/static/ImprovingMonitoringPages/image1.jpg" 
caption="Screenshot of new improved basemap and upstream basin shading for montitoring location [07016500](https://waterdata.usgs.gov/monitoring-location/07016500/#parameterCode=00065), Bourbeuse River at Union, MO"  alt="Screenshot of new improved basemap and upstream basin shading for monitoring location 07016500, Bourbeuse River at Union, MO" >}}




### 

# Get a snapshot of what data are available at a site

Users wanted to know what data were available on which dates. We added a
section to monitoring location pages that summarizes data availability
for each site. The “Summary of All Available Data” section shows the
start and end date of available data at each site. We grouped parameters
into categories to make the available data easier to understand.

{{< figure src="/static/ImprovingMonitoringPages/image2.jpg" 
caption="A screenshot of a data summary section from monitoring location [07019130](https://waterdata.usgs.gov/monitoring-location/07019130/#parameterCode=00065), Meramec River at Valley Park, MO"  alt=" screenshot of a data summary section from monitoring location 07019130, Meramec River at Valley Park, MO" >}}




###

The period of record is also now displayed on the monitoring location
pages for instantaneous values of each parameter, making it easier to
request a custom time period to display on the hydrograph.

{{< figure src="/static/ImprovingMonitoringPages/image3.jpg" 
caption="A screenshot showing the period of record for instantaneous values at monitoring location [07019130](https://waterdata.usgs.gov/monitoring-location/07019130/#parameterCode=00065), Meramec River at Valley Park, MO"  alt="A screenshot showing the period of record for instantaneous values at monitoring location 07019130, Meramec River at Valley Park, MO" >}}




### 



# Make the hydrograph easier to view and manipulate

-   Users commonly asked for better ways to manipulate the timeline
    displayed on the hydrograph. Our team improved the ways users
    interact with dates by incorporating the [U.S. Web Design System
    date
    picker](https://designsystem.digital.gov/form-controls/05-date-picker/)
    in the “Custom” date section. Users can now select a custom date
    frame by choosing dates on a calendar or typing dates.

###


{{< figure src="/static/ImprovingMonitoringPages/image4.jpg" 
caption="A screenshot of updated date picker for hydrograph display"  alt="A screenshot of updated date picker for hydrograph display" >}}



###

-   They asked for easier ways to switch between parameters, especially
    on mobile devices. Our team changed the way that parameters are
    displayed on our pages by adding “radio buttons” so that it was
    easier for users to switch between parameters displayed on the
    hydrograph.

-   Users also asked that we take the parameter code number off the
    display so there is less text on the screen. We shortened the names
    of parameters displayed by moving the USGS parameter codes (commonly
    referred to as “p-codes”) into tool tips, which users access by
    hovering over the icon at the end of the parameter name.

###



{{< figure src="/static/ImprovingMonitoringPages/Gif.gif" 
caption="Example of how to switch between parameters at monitoring location [09405500](https://waterdata.usgs.gov/monitoring-location/09405500/#parameterCode=00065), North Fork Virgin River near Springdale, UT" alt="xample of how to switch between parameters at monitoring location 09405500, North Fork Virgin River near Springdale, UT" >}}






###

-   Others requested that we switch the colors on the hydrograph so that
    historic and statistical data are easier to view. Our team made these changes and also
    improved how the hydrograph looks on the page. We changed the color
    and thickness of median data and historic data so that they are
    easier to view.

### 

# Add links to other USGS services

-   Users asked us to add links to make our other services more
    accessible to them. Our team responded by adding links to
    [WaterAlert](https://maps.waterdata.usgs.gov/mapper/wateralert/) for
    parameters of interest at the top of the menu/table where users also
    see the period of record. These links take users directly to a
    subscription form for the site where they set notification
    thresholds.

###

{{< figure src="/static/ImprovingMonitoringPages/image5.jpg" 
caption="Example of WaterAlert Subscription Form for monitoring locaiton [01458500](https://waterdata.usgs.gov/monitoring-location/01458500/#parameterCode=00065), Delaware River at Frenchtown, NJ" alt="Example of WaterAlert Subscription Form" >}}
###

-   Users wanted to be able to download data. We added links to
    different methods for downloading data. These links point to data
    available from USGS Water Data Services and are limited to
    instantaneous data available in the hydrograph. We also encourage
    users to use the dataRetrieval package in R, which allows users to
    access an expanded data set for each site.


{{< figure src="/static/ImprovingMonitoringPages/image6.jpg" 
title="Screen capture of data download section" alt="Screen capture of data download section" >}}


### 
