---
title: "Home Page"
date: 2018-07-30T21:24:35-05:00
draft: false
---

<p align="center">
  <font size="10">Welcome to Document Research!</font>
</p>

Document Research (DocuRe) is a web n-tier application that allows simple search as well as complex machine learning on small or large amounts of text.

| first | second | third |
|:--|:--|:--|
|{{% alert theme="danger" %}}Danger{{%/alert%}}|{{% alert theme="warning" %}}Warning{{%/alert%}}|{{% alert theme="info" %}}Info{{%/alert%}}|

### parameters

| Parameter | Default | Description |
|:--|:--|:--|
| title | "Attachments" | List's title  |
| pattern | ".*" | A regular expressions, used to filter the attachments by file name. <br/><br/>{{%alert warning%}}The **pattern** parameter value must be [regular expressions](https://en.wikipedia.org/wiki/Regular_expression).

For example:

* To match a file suffix of 'jpg', use **.*jpg** (not *.jpg).
* To match file names ending in 'jpg' or 'png', use **.*(jpg|png)**

{{%/alert%}}|

