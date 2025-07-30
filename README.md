# uaconst

A Go package with constants for the latest browser User-Agent and `sec-ch-ua` headers.

## Usage

```go
import "github.com/igolaizola/uaconst"

req.Header.Set("User-Agent", uaconst.DefaultUserAgent)
req.Header.Set("sec-ch-ua", uaconst.DefaultSecChUa)
```

## Update constants

Open https://httpbin.org/response-headers?Accept-CH=Sec-CH-UA-Full-Version-List%2CSec-CH-UA-Platform-Version in your browser and copy the `sec-ch-ua` headers and `user-agent` header to the `uaconst` package.
