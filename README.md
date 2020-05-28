# fflib-vscode-snippets
Adds snippets to vscode related to common tasks used in the [fflib apex library](https://github.com/apex-enterprise-patterns/fflib-apex-common) and [apex mocks](https://github.com/apex-enterprise-patterns/fflib-apex-mocks).

## Included Snippets
| Name | Prefix | Description |
|-----| ------ | --- |
|Generate Id|fflib-generate-id|Generate an id using `fflib_IdGenerator`|
|Apex Mocks|fflib-apex-mocks|Create a new instance of `fflib_ApexMocks`|
|Mock Class|fflib-mock-class|Mock a class with `fflib_ApexMocks.mock()`|
|Stubbing|fflib-stub|Add method calls to start and stop stubbing|
|Then Return|fflib-then-return|Stub a method with `fflib_ApexMocks.when().thenReturn()`|
|Then Throw|fflib-then-throw|Stub an exception with `fflib_ApexMocks.when().thenThrow()`|
|Do Throw When|fflib-do-throw|Stub an exception with `fflib_ApexMocks.doThrowWhen()`|
|Set Selector Mock|fflib-set-selector-mock|Tell the selector factory to return a mocked selector|
|Set Service Mock|fflib-set-service-mock|Tell the service factory to return a mocked service|
|Set Unit of Work Mock|fflib-set-uow-mock|Tell the unit of work factory to return a mocked unit of work|
|Set Domain Mock|fflib-set-domain-mock|Tell the domain factory to return a mocked domain|
|Verification|fflib-verify|Insert a new call to `fflib_ApexMocks.verify()`|


