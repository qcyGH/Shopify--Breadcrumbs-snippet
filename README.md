# Shopify: Breadcrumbs snippet
![Preview](https://github.com/qcyGH/Shopify--Breadcrumbs-snippet/blob/main/images_for_github/preview.png "Preview")

## Description
Its a breadcrumbs snippet, that adapts to template where its using. Project include breadcrumbs snippet, arrow snippet (its using inside breadcrumbs) and styles.

## How to use

1. Download the project.
2. Past all from `breadcrumbs` folder to your theme folder.
3. If you wanna use my styles for breadcrumbs, you need to connect styles where you wanna use breadcrumbs like this:

```liquid

{{ 'breadcrumbs.css' | asset_url | stylesheet_tag }}

```
4. Use snippet where you need it.

```liquid

{% render 'breadcrumbs' %}

```
5. Enjoy (～￣▽￣)～

## Code

### Breadcrumbs snippet code
![Breadcrumbs snippet code](https://github.com/qcyGH/Shopify--Breadcrumbs-snippet/blob/main/images_for_github/breadcrumbs.png "Breadcrumbs snippet code")

### Breadcrumbs styles
![Breadcrumbs styles](https://github.com/qcyGH/Shopify--Breadcrumbs-snippet/blob/main/images_for_github/styles.png "Breadcrumbs styles")

### Icon arrow snippet
![Icon arrow snippet](https://github.com/qcyGH/Shopify--Breadcrumbs-snippet/blob/main/images_for_github/arrow.png "Icon arrow snippet")
