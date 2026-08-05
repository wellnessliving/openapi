# WellnessLiving OpenAPI

Interactive API documentation for the WellnessLiving platform, rendered with [Redoc](https://redocly.com/redoc/) and [Swagger UI](https://swagger.io/tools/swagger-ui/).

**GitHub Pages:** https://wellnessliving.github.io/openapi/

## Versions

| Version         | Docs                                                                 | OpenAPI spec                            |
|-----------------|----------------------------------------------------------------------|-----------------------------------------|
| **Production**  | [/production/](https://wellnessliving.github.io/openapi/production/) | [openapi.yaml](production/openapi.yaml) |
| **Stable**      | [/stable/](https://wellnessliving.github.io/openapi/stable/)         | [openapi.yaml](stable/openapi.yaml)     |
| **Development** | [/dev/](https://wellnessliving.github.io/openapi/dev/)               | [openapi.yaml](dev/openapi.yaml)        |

## Structure

```
production/
  openapi.yaml     - OpenAPI 3.1 specification
stable/
  openapi.yaml     - OpenAPI 3.1 specification
dev/
  openapi.yaml     - OpenAPI 3.1 specification
docs/
  index.html       - version picker landing page
  redoc.html       - Redoc viewer
  swagger.html     - Swagger UI viewer
```

## Related repositories

- [JS SDK](https://github.com/wellnessliving/wl-openapi-js)
- [PHP SDK](https://github.com/wellnessliving/wl-openapi-php)

## Links

- [WellnessLiving](https://www.wellnessliving.com)
- [Terms of Use](https://www.wellnessliving.com/knowledge-sharing/terms-of-use/)
- [Support](https://www.wellnessliving.com/support)