# base.css
Base CSS to start a design system

## Usage

```
npm i mcssbase
```

**Html**

```html
<link rel="stylesheet" href="<mcssbase_root>/dist/css/base.css" />
<!-- or use the minified version -->
<link rel="stylesheet" href="<mcssbase_root>/dist/css/base.min.css" />
```

**JS**

```javascript
import 'mcssbase/dist/css/base.css';
// or use the minified version
import 'mcssbase/dist/css/base.min.css';
```


## Starting with Bootstrap 

The following wheels are not to be reinvented.
### Reboot
https://getbootstrap.com/docs/5.0/content/reboot/

### Breakpoints
https://getbootstrap.com/docs/5.0/layout/breakpoints/
### Grid system
https://getbootstrap.com/docs/5.0/layout/grid/


### Colours
@TODO


### Utilities
Following utilities are included in base.css
- Display: https://getbootstrap.com/docs/5.0/utilities/display/
- Flex: https://getbootstrap.com/docs/5.0/utilities/flex/
- Spacing: https://getbootstrap.com/docs/5.0/utilities/spacing/
  - *Note* We have overwritten the Boostrap spacing map `$spacers` to use CSS variable `--base-spacing`, see below.

## CSS Variables
| Name | Description | Default |
| ---- | ----------- | ------- |
| `--base-spacing` | Base value for spacing utilities such as `.mt-*` and `.pb-*` | `8px` | 
|`--color-*`| Colour names | 
