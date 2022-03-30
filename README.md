# Decidim
## Source description
Decidim is a participatory democracy framework, written in Ruby on Rails, originally developed for the Barcelona City government online and offline participation website. Installing these libraries will provide you a generator and gems to help you develop web applications like the ones found on example applications or like our demo application.

All members of the Decidim community agree with Decidim Social Contract or Code of Democratic Guarantees.

See decidim repository [here](https://github.com/decidim/decidim) and the website [here](https://decidim.org)

## How to use this project
This project gathers all data related to the [dashboard_automation](https://github.com/OpenSourcePolitics/dashboard_automation)

The project is organized followingly: each folder gives all possible cards you can create about a topic. As instance, if your data source is about employee managament, you can have a `employee` folder with this architecture.
```bash
...
├── employee
│   ├── info.yml
│   └── locales
│       └── en.yml
...
```

You have to complete the `info.yml` and locales following asked informations.
In order to understand how to create cards automatically through the Metabase API, please see [dashboard_automation documentation](https://github.com/OpenSourcePolitics/dashboard_automation/blob/master/README.md)