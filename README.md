---
description: 'Building on TachySwap and need help? let us know.'
---

## How to get your token LOGO on TachySwap:

### 1. Image for the Token Logo <a id="1-image-for-the-token-logo"></a>

> * **File Extension**: `png` . Uppercase `PNG` is considered invalid
> * **File Name**：`logo.png`
> * **Background**: Transparent is a must
### 2. Token Information File <a id="2-token-information-file"></a>

> * Fork the repository and add the token information (example below) to tokenlist/tokenlist.json
> * Create a folder under token/addresses/{tokenAddress}
> * Add the token icon (logo.png) under the folder created in the previous step
> * Add the token information in the tokenlist.json file, in the format shown below
The sample below shows what information has to be included on the `tokenlist.json` file.  
Please make sure that the details are accurate and follows the formatting.

```
{
            "chainId": 42793,
            "address": "0xc9B53AB2679f573e480d01e0f49e2B5CFB7a3EAb",
            "decimals": 18,
            "name": "Wrapped XTZ",
            "symbol": "WXTZ",
            "logoURI": "https://raw.githubusercontent.com/tachyswap/tokenlist/main/token/addresses/0xc9B53AB2679f573e480d01e0f49e2B5CFB7a3EAb/logo.png"
}
``` 

The Pull request will be screened before it gets added to the repository. In order to get approved, your submission must meet the following requirements.

* **Project has a website.**
* **Has a social media presence.**
* **Project must have a significant amount of liquidity and volume.**
* **Verified Contract.**
* **Detailed Token Information.**
