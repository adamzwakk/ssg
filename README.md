# ssg
A static website generator written in bash

This is a fork of ssg written by Roman Zolotarev which you can find [here](https://www.romanzolotarev.com/ssg.html)

#### How my fork differs
- Fixed sitemap.xml generation to base its modified time off the src .md files
- Fixed h1 tags to generate even if a title already exists, just prepend as if no title was there
- lowdown no longer adds weird header ids to output
- Automatically adds (Updated $time) divs after the h1 tags based on the mod time of the src md (except the index)
