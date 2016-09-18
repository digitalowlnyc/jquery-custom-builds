# jquery-custom-builds

Custom jQuery builds

## Build Command Template

`-ajax/xhr, -ajax/script, -ajax/jsonp, -css, -css/showHide, -deprecated, -dimensions, -effects, -event, -event/alias, -event/focusin, -event/trigger, -offset, -wrap, -core/ready, -deferred, -exports/global, -exports/amd, -sizzle`

## Build Index

- **ajax-only**: Ajax only version, excluding script and jsonp ajax transports. Does not use "sizzle" selector library, so only basic selectors are supported.
  - build command: `grunt custom: -ajax/script, -ajax/jsonp, -css, -css/showHide, -deprecated, -dimensions, -effects, -event, -event/alias, -event/focusin, -event/trigger, -offset, -wrap, -exports/amd, -sizzle`
