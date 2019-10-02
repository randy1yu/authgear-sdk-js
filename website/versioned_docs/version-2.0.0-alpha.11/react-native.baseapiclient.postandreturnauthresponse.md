---
id: version-2.0.0-alpha.11-react-native.baseapiclient.postandreturnauthresponse
title: BaseAPIClient.postAndReturnAuthResponse() method
hide_title: true
original_id: react-native.baseapiclient.postandreturnauthresponse
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->


## BaseAPIClient.postAndReturnAuthResponse() method

<b>Signature:</b>

```typescript
protected postAndReturnAuthResponse(path: string, options?: {
        json?: JSONObject;
        query?: [string, string][];
        autoRefreshToken?: boolean;
    }): Promise<AuthResponse>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  path | <code>string</code> |  |
|  options | <code>{</code><br/><code>        json?: JSONObject;</code><br/><code>        query?: [string, string][];</code><br/><code>        autoRefreshToken?: boolean;</code><br/><code>    }</code> |  |

<b>Returns:</b>

`Promise<AuthResponse>`
