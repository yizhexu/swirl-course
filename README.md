swirl courses
=============

This is a collection of interactive aWhere weather api courses developed with [swirl R package](http://swirlstats.com). You'll find instructions for installing courses further down on this page. Some courses are still in development and we'd love to hear any [suggestions](https://github.com/yizhexu/swirl_course/issues/new) you have as you work through them.

Here are our current offerings, organized by level of difficulty:

#### Getting Data from API with R ####

Step by step instructions to get aWhere weather data with the weather API. 

- Basic Weather
- Advanced Weather (under devleopment)


## Install and run a course manually

Here's a simple way to install a swirl course.

1) Click on the **Download ZIP** button on the righthand side of this page.

2) Enter the following from the R console, **substituting the correct file path** to your downloaded file and the **name of your desired course**:

```
library(swirl)
install_course_zip("path/to/file/here/swirl_course-master.zip", multi=TRUE, 
                   which_course="Course Name Here")
swirl()
```

For example, if you download the zip file to `~/Downloads/swirl_course-master.zip`, then the following command will install the Getting Data from API with R course.

```
install_course_zip("~/Downloads/swirl_course-master.zip", multi=TRUE, which_course="Getting_Data_from_API_with_R")
```

**Please note that course names are case sensitive!**

Although we recommend you install one course at a time, if you omit the `which_course` argument, then all available courses from this repository will be installed:

```
install_course_zip("~/Downloads/swirl_courses-master.zip", multi=TRUE)
```

## Uninstall a course

If you'd like to remove a course at any time, you can use `uninstall_course("Course Name Here")`.

