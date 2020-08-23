**Fully Coded Components**

Vue Argon Dashboard is built with over 100 individual components, giving you the freedom of choosing and combining. All components can take variations in color, that you can easily modify using SASS files.
You will save a lot of time going from prototyping to full-functional code, because all elements are implemented. This Dashboard is coming with pre-built examples, so the development process is seamless, switching from our pages to the real website is very easy to be done.
Every element has multiple states for colors, styles, hover, focus, that you can easily access and use.

If you want to get inspiration or just show something directly to your clients, you can jump start your development with our pre-built example pages. You will be able to quickly set up the basic structure for your web project.


## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## File Structure
Within the download you'll find the following directories and files:

```
|-- Vue Argon Dashboard
    |-- .gitignore
    |-- CHANGELOG.md
    |-- ISSUES_TEMPLATE.md
    |-- LICENSE.md
    |-- README.md
    |-- babel.config.js
    |-- package.json
    |-- public
    |   |-- favicon.ico
    |   |-- index.html
    |   |-- manifest.json
    |   |-- robots.txt
    |   |-- img
    |-- src
        |-- App.vue
        |-- main.js
        |-- registerServiceWorker.js
        |-- router.js
        |-- assets
        |   |-- logo.png
        |   |-- scss
        |   |   |-- argon.scss
        |   |-- vendor
        |       |-- @fortawesome
        |       |-- nucleo
        |-- components
        |   |-- Badge.vue
        |   |-- BaseAlert.vue
        |   |-- BaseButton.vue
        |   |-- BaseCheckbox.vue
        |   |-- BaseDropdown.vue
        |   |-- BaseHeader.vue
        |   |-- BaseInput.vue
        |   |-- BaseNav.vue
        |   |-- BasePagination.vue
        |   |-- BaseProgress.vue
        |   |-- BaseRadio.vue
        |   |-- BaseSlider.vue
        |   |-- BaseSwitch.vue
        |   |-- BaseTable.vue
        |   |-- Card.vue
        |   |-- CloseButton.vue
        |   |-- Modal.vue
        |   |-- NavbarToggleButton.vue
        |   |-- StatsCard.vue
        |   |-- stringUtils.js
        |   |-- Charts
        |   |   |-- BarChart.js
        |   |   |-- DoughnutChart.js
        |   |   |-- LineChart.js
        |   |   |-- PieChart.js
        |   |   |-- config.js
        |   |   |-- globalOptionsMixin.js
        |   |   |-- optionHelpers.js
        |   |-- SidebarPlugin
        |   |   |-- SideBar.vue
        |   |   |-- SidebarItem.vue
        |   |   |-- index.js
        |   |-- Tabs
        |       |-- PillsLayout.vue
        |       |-- Tab.vue
        |       |-- TabPane.vue
        |       |-- Tabs.vue
        |       |-- TabsLayout.vue
        |-- directives
        |   |-- click-ouside.js
        |-- layout
        |   |-- AuthLayout.vue
        |   |-- Content.vue
        |   |-- ContentFooter.vue
        |   |-- DashboardLayout.vue
        |   |-- DashboardNavbar.vue
        |   |-- LoadingMainPanel.vue
        |-- plugins
        |   |-- argon-dashboard.js
        |   |-- globalComponents.js
        |   |-- globalDirectives.js
        |-- views
            |-- Dashboard.vue
            |-- Icons.vue
            |-- Login.vue
            |-- Maps.vue
            |-- Register.vue
            |-- Tables.vue
            |-- UserProfile.vue
            |-- Dashboard
            |   |-- PageVisitsTable.vue
            |   |-- SocialTrafficTable.vue
            |-- Tables
                |-- ProjectsTable.vue
```