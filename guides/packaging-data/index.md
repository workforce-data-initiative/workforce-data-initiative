---
title: Packaging Data
---

You can package any kind of data as a Data Package.

1. Get your data together
   1. Get your data together in one folder (you can have data in subfolders of that folder too if you wish).
1. Add a datapackage.json file to package those data files into a useful whole (with key information like the license, title and format)
   1. The datapackage.json is a small file in JSON format that gives a bit of information about your dataset. You'll need to create this file and then place it in the directory you created.
   1. Don't worry if you don't know what JSON is - we provide some tools that can automatically create your this file for you.
   1. There are 2 options for creating the datapackage.json:
      1. Use the Data Packagist tool ({{ site.baseurl }}/tools/datapackagist/)
         1. Just answer a few questions and give it your data files and it will spit out a datapackage.json for you to include in your project
      1. Use the dpm commandline tool ({{ site.baseurl }}/tools/dpm/)
