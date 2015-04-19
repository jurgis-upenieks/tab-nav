# [VCL](https://github.com/vcl/doc) tab-nav

List of navigation items arranged as tabs.

## Features

## Usage

The selected tab is highlighted by a different background color.
A close-button is optional.
An icon button only tab, for example to open new tabs like in the first example,
can simply be created with the class `vclNopadding` and a standard button.

[basic example](/demo/example-basic.html)

Add the modifier class `vclTabStyleUni` for uni colored tabs.
This style is more suitable for showing tabs unobtrusively within
content textual for example.

[uni example](/demo/example-uni.html)

The content area of a tab panel can be built from various components
such as panels as shown in the panels examples
There is also a class `vclTabbable` to create a wrapper
element which adds proper margins for embedding
in other content and the `vclTabContent` and `vclTabPanel`
classes to lay out the content as shown in the uni style example.

By default tabs are directed as shown on the previous section.
Different directions are possible as shown below.

Modifier class `vclTabLeft`.

[left1 example](/demo/example-left.html)

[left2 example](/demo/example-uni-left.html)

Modifier class `vclTabRight`.

[right1 example](/demo/example-right.html)

[right2 example](/demo/example-uni-right.html)


## Classes

- `vclTabbable`
- `vclTabContent`
- `vclTabs`

## Modifiers

- `vclTabStyleUni`

## Variables

- `--tab-nav-color`
- `--tab-nav-hover-color`
- `--tab-nav-button-label-color`
- `--tab-nav-button-label-hover-color`
- `--tab-nav-button-selected-label-color`
- `--tab-nav-border-color`
- `--tab-nav-bg-color`
- `--tab-nav-bg-hover-color`
- `--tab-nav-bg-color--uni`

## Demo

[example.html](/demo/example.html) on GH-pages.
