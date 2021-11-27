# README

This is the initial version of CSS snippets extensions which helps you easy write media queries for vaious device sizes.

Install: https://marketplace.visualstudio.com/items?itemName=AjithGopi.css-snippets

## Resolution Breakpoints

This extension uses the Bootstrap 4 breakpoints. More info at https://getbootstrap.com/docs/4.0/layout/overview/#responsive-breakpoints

## File formats
* .css
* .scss
* .sass

## How to use (Life saver)
Every snippet prefix contains 3 parts:

1. Screen size:
    * extra-small
    * small
    * medium
    * large
    * extra-large
2. Scope:
    * Only the selected screen size (**screen-size**-only)
    * The selected screen size and larger (**screen-size**-and-up)
    * The selected screen size and smaller (**screen-size**-and-down)
3. Type:
	* Media Query (**screen-size-scope**-media-query)


## Snippets cheat-sheet

| Prefix | Result |
|---|---|
| small-devices-and-up-media-query | Small devices and larger (landscape phones, 576px and up) |
| medium-devices-and-up-media-query | Medium devices and larger (tablets, 768px and up) |
| large-devices-and-up-media-query | Large devices and larger (desktops, 992px and up) |
| small-devices-and-down-media-query | Small devices (landscape phones, Anything below 768px) |
| medium-devices-and-down-media-query | Medium devices (tablets, Anything below 992px) |
| large-devices-and-down-media-query | Large devices (laptops, desktops, Anything below 1200px) |
| extra-small-devices-only-media-query | Extra small devices only (portrait phones, Anything below 576px) |
| small-devices-only-media-query | Small devices only (landscape phones, Between 576px and 767px) |
| medium-devices-only-media-query | Medium devices only (laptops, desktops, Between 768px and 991px) |
| large-devices-only-media-query | Large devices (laptops, desktops, Between 992px and 1199px) |
| extra-large-devices-only-media-query | Extra Large devices only (desktops, 1200px and up) |

## Known Issues

Nothing. yet.

## Release Notes

Added media query snippets

### 1.0.0

Initial release

-----------------------------------------------------------------------------------------------------------
