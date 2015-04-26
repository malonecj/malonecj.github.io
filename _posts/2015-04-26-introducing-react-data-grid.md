---
layout: post
title: Introducing React Data Grid
published: true
---

At Adazzle, we've been working on a cool project for the past couple of months and we feel its finally ready for public use. It's a Javascript spreadsheet component built with React. We've been using it internally for quite some time, but have only recently gotten around to writing some decent [documentation](http://adazzle.github.io/react-data-grid/) and examples for it, as well as building up a proper test suite.

[ReactDataGrid](https://github.com/adazzle/react-data-grid/) started life off as a fork off an [exisitng project](https://github.com/prometheusresearch/react-grid) and the great work done by [Prometheus Research](https://github.com/prometheusresearch). The orginal project used virtual rendering techniques and harnassed the performance capabilities of React to be able to render hundreds of thousands of rows, and scroll through them without any lag. Since then, we’ve diverged significantly from the original project, and so moved to a new project [react-data-grid](https://github.com/adazzle/react-data-grid/). New features include

- Keyboard navigation
- [Fully editable grid](http://adazzle.github.io/react-data-grid/examples.html#/editable)
- [Rich cell editors like autocomplete, checkbox and dropdown editors, complete with keyboard navigation](http://adazzle.github.io/react-data-grid/examples.html#/editors)
- Custom cell Editors - Easily create your own
- [Custom cell Formatters](http://adazzle.github.io/react-data-grid/examples.html#/formatters)
- [Sorting](http://adazzle.github.io/react-data-grid/examples.html#/sortable) 
- Filtering
- Copy and Paste values into other cells
- Multiple cell updates using cell dragdown

Its available both from npm and bower
Simply run 
```sh
npm install react-data-grid
# or
bower install react-data-grid
```

Check out the examples and see how you get on
