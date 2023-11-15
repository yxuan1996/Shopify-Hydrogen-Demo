# Shopify-Hydrogen-Demo
Develop a Hydrogen Storefront

https://shopify.dev/docs/custom-storefronts/hydrogen/building

When creating a hydrogen storefront using `npm create`, a git repo is automatically initialized in the react app. 

This can result in files not being tracked in the main repo. 

To solve this, we need to remove the `.git` folder in `hydrogen-storefront`

The .git folder is hidden in vscode. To view it, go to file -> preferences -> settings and in the search bar, search for "files.exclude". Remove .git folder from the exclusion list. 

DO NOT remove the .git folder in the main directory. Only delete the one in the `hydrogen-storefront` subdirectory. 

### Running the app
```
cd hydrogen-storefront && npm run dev
```