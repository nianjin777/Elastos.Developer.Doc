## getidentificationtxbyidandpath

description: get registered id transaction by id and path
parameters:

| name | type   | description            |
| ---- | ------ | ---------------------- |
| id   | string | id of identification   |
| path | string | path of identification |

results: registered id transaction information
argument sample:

```json
{
	"method": "getidentificationtxbyidandpath",
	"params":{
		"id":"igRn4VtAUB7hPkMrYMHt5f3xiQUMQJUFD2",
		"path": "kyc/person/identityCard"
	}
}
```

result sample:

```json
{
  "result": {
    "txid":"277f428f0be9f60bf3ba996540f3a4b467ac75f1296d41b5543edcc3190d944e",
    "hash":"277f428f0be9f60bf3ba996540f3a4b467ac75f1296d41b5543edcc3190d944e",
    "size":733,
    "vsize":733,
    "version":0,
    "locktime":0,
    "vin":[
        {
            "txid":"860b98c591d88c2eeaea521c32d35f191e1d039378c58bf47bbaf7752ecaa9ca",
            "vout":0,
            "sequence":4294967295
        }
    ],
    "vout":[
        {
            "value":"0",
            "n":0,
            "address":"igRn4VtAUB7hPkMrYMHt5f3xiQUMQJUFD2",
            "assetid":"a3d0eaa466df74983b5d7c543de6904f4c9418ead5ffd6d25814234a96db37b0",
            "outputlock":0
        },
        {
            "value":"98.99990000",
            "n":1,
            "address":"EfdVME9U6u1e774R4YeXpPQN3vLVsmmkee",
            "assetid":"a3d0eaa466df74983b5d7c543de6904f4c9418ead5ffd6d25814234a96db37b0",
            "outputlock":0
        }
    ],
    "blockhash":"5ac927a80e58e4337ee791c4c3e7c0d40f54ab6b63efb11ece9630259a57dbc3",
    "confirmations":10,
    "time":1539155763,
    "blocktime":1539155763,
    "type":9,
    "payloadversion":0,
    "payload":{
        "Id":"igRn4VtAUB7hPkMrYMHt5f3xiQUMQJUFD2",
        "Sign":"40bc9424152e20c20909909d87036a4f54e8e30e7ecce65b235e41dac2cf0ea8954c93453e6b275963baf77ea71470123f70a83053327d071ead86315e685e564b",
        "Contents":[
            {
                "Path":"kyc/person/identityCard",
                "Values":[
                    {                      "DataHash":"bd117820c4cf30b0ad9ce68fe92b0117ca41ac2b6a49235fabd793fc3a9413c0",
                     "Proof":""signature":"30450220499a5de3f84e7e919c26b6a8543fd24129634c65ee4d38fe2e3386ec
8a5dae57022100b7679de8d181a454e2def8f55de423e9e15bebcde5c58e871d20aa0d91162ff6","notary
":"COOIX""
                    }
                ]
            }
        ]
    },
    "attributes":[
        {
            "usage":0,
            "data":"31353831333330393234"
        },
        {
            "usage":145,
            "data":"6d656d6f"
        }
    ],
    "programs":[
        {
            "code":"2103e1963a35418da50a0b2749c901fd246b08522e5fa192cb1f3a2de8a9785eeeefad",
            "parameter":"400f0ecff1d11fae00dbad8ab70966bb3e6e2879978dadc322a73d5e5236cf5818adacf059777a904eec8e6dd15f97bc1422d861af9e9c837a32b70d0f623970f6"
        },
        {
            "code":"21027035769801eee0fd34b76a11a251dfcde5f0e763a626e93af905c4c0d382334fac",
            "parameter":"40e024b0d2465ec851fc56db1118f05e2c083320c30610c4850aa632d0187f5ccb0d70840044f2e1daab9e677baa4fd86e569d91a1438fe0fb8c7f2974d567f4fe"
        }
    ]
  }
}
```