# \<id-panel\>

Idaho panel element

## Installation

Add the following to bower.json.

```JSON
{
  "id-panel": "https://github.com/accessidaho/egov-id-panel.git"
}
```

## Usage

Import the element:

```html
<link rel="import" href="bower_components/id-panel/id-panel.html">
```

Add the element and set properties:

```html
<id-panel color="[success, warning, danger]" title="Panel Title">Panel Body</id-panel>
```

## Styling

`<id-panel>` provides the following custom properties for styling:

Custom property | Description | Default
----------------|-------------|----------
`--id-primary-light-border` | Default border color | #d9edf7
`--id-primary-light` | Default background color | #eef7fb
