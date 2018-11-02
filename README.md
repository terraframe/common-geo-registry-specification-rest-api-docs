# Common Geo-Registry Specicification REST OpenAPI Specification
[![Build Status](https://travis-ci.org/terraframe/common-geo-registry-specification-rest-api-docs.svg?branch=master)](https://travis-ci.org/terraframe/common-geo-registry-specification-rest-api-docs)

## About

These docs where generated with [ReDoc](https://github.com/Rebilly/ReDoc) from an OpenAPI specification that defines the [Common Geospatial Registry REST API](https://github.com/terraframe/common-geo-registry-specification).

## Links

- Documentation(ReDoc): https://terraframe.github.io/common-geo-registry-specification-rest-api-docs/
- SwaggerUI: https://terraframe.github.io/common-geo-registry-specification-rest-api-docs/swagger-ui/
- Look full spec:
    + JSON https://terraframe.github.io/common-geo-registry-specification-rest-api-docs/swagger.json
    + YAML https://terraframe.github.io/common-geo-registry-specification-rest-api-docs/swagger.yaml
- Preview spec version for branch `[branch]`: https://terraframe.github.io/common-geo-registry-specification-rest-api-docs/preview/[branch]

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification

### From editing the configuration directly in GitHub
It's often easier to make small changes to the OpenAPI spec these docs are rendered from by editing the configuration file directly in GitHub through a web browser. This project uses continuous integration with Travis CI to re-render the docs for every commit pushed to this repository. Since that configuration is hosted in the [formal Common Geospatial Registry specification repository](https://github.com/terraframe/common-geo-registry-specification/blob/master/1.0/registry-interface/rest-api.yaml) outside of this project any change made there through the browser will not be reflected in these docs. To re-render the docs manually simply trigger the build manually through the [Travic CI user interface](https://travis-ci.com/terraframe/common-geo-registry-specification-rest-api-docs)


### In a development environment
#### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

#### Development

1. Run `npm start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing https://terraframe.github.io/common-geo-registry-specification-rest-api-docs/ with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
6. Share you changes with the rest of the world by pushing to GitHub :smile:
