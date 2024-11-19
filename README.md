# WebJar pivot table | Flexmonster Pivot Table & Charts WebJar to use with Maven
[![Flexmonster Pivot Table & Charts](https://cdn.flexmonster.com/readmes/blazor.webp)](https://www.flexmonster.com?r=sample_blz)
Website: [flexmonster.com](https://www.flexmonster.com?r=sample_blz)

[![Github Stars](https://img.shields.io/github/stars/flexmonster?style=social)](https://github.com/flexmonster) [![Twitter](https://img.shields.io/twitter/follow/Flexmonster?style=social)](https://twitter.com/Flexmonster)

## Flexmonster Pivot Table & Charts

Flexmonster Pivot Table & Charts is a powerful and fully customizable JavaScript component for web reporting. It is packed with all core features for data analysis and can easily become a part of your Blazor data visualization project. The tool supports popular frameworks like Angular, React, Vue, Blazor, and [more](https://www.flexmonster.com/doc/available-tutorials-integration?r=sample_blz). Also, Flexmonster connects to any data source, including SQL and NoSQL databases, JSON and CSV files, OLAP cubes, and Elasticsearch. 

This repository contains a simple [Maven](https://maven.apache.org) project for Flexmonster Pivot Table & Charts.

Table of contents:

* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [What is inside the project](#what-is-inside-the-project)
* [Related Flexmonster docs](#related-flexmonster-docs)
* [Support and feedback](#support-and-feedback)
* [Flexmonster licensing](#flexmonster-licensing)
* [Social media](#social-media)

## Prerequisites
<ul>
 <li>Maven</li>
 <li>Java 8+ version</li>
 <li>JRE (Eclipse, IntelliJ IDEA ... )</li>
 <li>JavaScript and HTML (optionally) </li>
</ul>

## Installation

1. Ensure Maven is installed:
 ```
 mvn -v
```

3. Download a `.zip` archive with the sample project or clone it from GitHub with the following command:

```bash
git clone https://github.com/webjars/flexmonster.git
```

3. Run the sample project from the console:
   
```
cd flexmonster
```

4. Install the WebJar locally:
```
mvn install
```

This command will:
<ul>
 <li> Download dependencies </li>
 <li> Build the JAR file </li>
 <li> Install it to your local Maven repository </li>
</ul>

5. Add the dependency to your project:
``` 
<dependency>
    <groupId>org.webjars</groupId>
    <artifactId>flexmonster</artifactId>
    <version>2.9.91-SNAPSHOT</version>
</dependency>
```

6. Reference in HTML:
   ``` 
   <script src="/webjars/flexmonster/2.9.91-SNAPSHOT/flexmonster.full.min.js"></script>
   <link href="/webjars/flexmonster/2.9.91-SNAPSHOT/flexmonster.min.css" rel="stylesheet">
   ```

More info: http://webjars.org

Upstream: https://www.flexmonster.com/
