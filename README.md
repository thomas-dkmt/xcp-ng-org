# XCP-ng website & documentation


## Website

Our website is a simple and static HTML page.

## Documentation

Our documentation is built using [Docusaurus 3](https://docusaurus.io/), a modern static website and documentation generator. It's available at https://docs.xcp-ng.org

**Note:** The sidebar contents used to be generated automatically. Since we've moved to Docusaurus, the contents are declared manually. When creating a new page, make sure to add it to sidebars.js or it may not appear in the sidebar.

### Installation

```
$ npm i
```

### Local Development

```
$ npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.


### Autogeneration

This documentation is automatically rebuilt after each push event on `master` branch.