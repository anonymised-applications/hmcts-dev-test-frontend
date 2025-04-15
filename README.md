# HMCTS Dev Test Frontend
This will be the frontend for the brand new HMCTS case management system. As a potential candidate we are leaving
this in your hands. Please refer to the brief for the complete list of tasks! Complete as much as you can and be
as creative as you want.

To begin with, you should be able to run this by running:
1) `yarn install`
2) `yarn webpack`
3) `yarn start:dev` or navigate to package.json and run the script manually

You can change the structure however you like! 

-specified yarn version to match existing version
-app would run but intellisense giving false errors, update sdk settings to fix
-app would not run, red herring error, .pnp.cjs in home dir was cause of issue
-more false error due to express version and express types version mismatch
- yarn berry pnp errors fixed by forced mismatch or typescript version between sdk and package.json - using pnpm instead
- updating deprecated dependencies