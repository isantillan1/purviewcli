# pv share deleteSentShare

[Command Reference](../../../README.md#command-reference) > [share](./main.md) >  deleteSentShare

## Description

Deletes a sent share.

## Syntax

```
pv share deleteSentShare --sentShareName=<val>
```

## Required Arguments

`--sentShareName` (string)

The name of the sent share.

## Optional Arguments

*None*

## API Mapping

Share Data Plane > Sent Shares > [Delete](https://docs.microsoft.com/en-us/rest/api/purview/sharedataplane/sent-shares/delete)
```
DELETE https://{accountName}.purview.azure.com/share/sentShares/{sentShareName}
```

## Examples

Description
```powershell
pv share _EXAMPLE_
```


<details><summary>Sample response.</summary>
<p>

```json
{
    "key": "value"
}
```
</p>
</details>
