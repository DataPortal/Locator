# Modification Notes

SUMO = Awesome NGX Starter Kit
> https://github.com/xmlking/ngx-starter-kit
> https://xmlking.github.io/ngx-starter-kit/home

NGXS resources
https://ngxs.gitbook.io/ngxs/community/resources

<h2>Changes made during setup</h2>

Home page route:
libs/home/src/lib/containers/landing.component.html

Commented out "Get started" button.

Default page title set in:
apps/webapp/src/app/core/services/page-title.service.ts:

Top Bar
libs/home/src/lib/components/header/header.component.html

Navigation in home
libs/home/src/lib/components/header/header.component.ts

Top Bar navigation paths
libs/home/src/lib/home.module.ts

Commented out "Intro" link.

About - Changed title, added View Map button, removed Features button
libs/home/src/lib/containers/about/about.component.html

Accounts Grid List
libs/grid/src/lib/containers/accounts-grid-list

Displayed User data from random account service defined in:
libs/grid/src/lib/services/random-account.service.ts
https://randomuser.me/api/?seed=datauser&nat=us&exc=login,registered&results=100

Replaced sumo, sumo1, sumo2, sumo3 with datauser, datauser1, datauser2, datauser3

Copied accounts-grid-list to home...containers and renamed to vehicles.

Copied blog folder, renamed to coordmap.

Commented out SHARE and LIKE on users list sample
Commented out logo assets/img/logo_text.png and assets/img/logo_text_dark.png
