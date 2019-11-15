# Convox Create Action
This Action [creates](https://docs.convox.com/deployment/creating-an-application) an app in a Convox Rack

## Inputs
### `rack`
**Required** The name of the [Convox Rack](https://docs.convox.com/introduction/rack) you wish to create the app in.
### `app`
**Required** The name of the [app](https://docs.convox.com/deployment/creating-an-application) you wish to create.
## Example usage
```
uses: convox/action-create@v1
with:
  rack: staging
  app: myapp
```