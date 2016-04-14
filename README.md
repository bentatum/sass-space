# sass-space
A set of css class names for quick and simple spacing using css classes.

## Setup:

In your style.scss:

```scss
// Define your spacing constants before importing sass-space

$spacing-xxsmall: 0.1rem;
$spacing-xsmall: 0.3rem;
$spacing-small: 0.5rem;
$spacing-medium: 1rem;
$spacing-large: 2rem;
$spacing-xlarge: 4rem;

@import "~/sass-space/index";
```

This gives you xxs, xs, s, m, l, xl and xxl in all directions in both margin and padding.

Here are all the class names sass-space gives you.

Margin:

mtxxs, mtxs, mts, mtm, mtl, mtxl, mtxxl,  
mrxxs, mrxs, mrs, mrm, mrl, mrxl, mrxxl,  
mbxxs, mbxs, mbs, mbm, mbl, mbxl, mbxxl,  
mlxxs, mlxs, mls, mlm, mll, mlxl, mlxxl

Padding:

ptxxs, ptxs, pts, ptm, ptl, ptxl, ptxxl,  
prxxs, prxs, prs, prm, prl, prxl, prxxl,  
pbxxs, pbxs, pbs, pbm, pbl, pbxl, pbxxl,  
plxxs, plxs, pls, plm, pll, plxl, plxxl
