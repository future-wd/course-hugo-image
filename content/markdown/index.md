---
title: "Markdown"
date: 2022-03-02T23:58:42-05:00
draft: false
menu: main
weight: 70
type: markdown
---
Below are examples of the different implementations of the image partial with markdown.

{{< image src="images/placeholder1.jpg" alt="Alt" title="Title" widths="300,600,900">}}
Image via shortcode

{{< figure src="images/placeholder1.jpg" caption="Image/Figure caption" figureTitle="Image/Figure title"  width="300">}}
Image via shortcode

![Alt Text (.PlainText)](images/placeholder2.jpg "Title (.Title)")
Image via markdown with render-hook
