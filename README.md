# AzureFunctionCoreTools-localsettingsjson
Repository used to test and reproduce whether AzureFunctionCoreTools is hard-coded to use local.settings.json.

## Commands used to reproduce

### Create Project using default command from help documentation
https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=linux%2Cisolated-process%2Cnode-v4%2Cpython-v2%2Chttp-trigger%2Ccontainer-apps&pivots=programming-language-csharp
```
func init MyProjFolder --worker-runtime dotnet-isolated --target-framework net7.0
cd MyProjFolder
func new --template "Http Trigger" --name MyHttpTrigger --target-framework net7.0
func start
```
