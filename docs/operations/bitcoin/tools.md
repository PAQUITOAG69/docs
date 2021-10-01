
``` sh
curl https://nd-111-639-677.p2pify.com/a5a80713a6036780d64fed1f52fe33cc -d '{"method":"getblockchaininfo","params":[],"id":1}'
```

</template>
<template v-slot:pp

</template>
</CodeSwitcher>

## Development tools

### Python

``` python
from bitcoincli import Bitcoin

host = "nd-111-639-677.p2pify.com"
port = "80"
username = "hardcore-booth"
password = "fling-uptake-daily-ankle-citrus-maggot"

bitcoin = Bitcoin(username, password, host, port)
```

3. Invoke any methods from the [Bitcoin API specification](https://bitcoin.org/en/developer-reference#bitcoin-core-apis):

``` python
info = bitcoin.getblockchaininfo()
print(info)
```

