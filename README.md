# gove-api



## Request JSON

```
curl: http://localhost:8080/gove-api/rest/v1/nfe/listByDate?dataInicial=2018-07-01&dataFinal=2018-09-30&start=1&max=1000
```

## Response JSON

```
[
    {
        "razaoSocial": "SIMETRYA TECNOLOGIA DA INFORMACAO LTDA",
        "chave": "51180708939203000150550010000012431076553472",
        "cnpj": "8939203000150",
        "nfe": "1243",
        "dataEmissao": "2018-07-26 00:00:00.0"
    },
    {
        "razaoSocial": "SIMETRYA TECNOLOGIA DA INFORMACAO LTDA",
        "chave": "51180708939203000150550010000012461951593800",
        "cnpj": "8939203000150",
        "nfe": "1246",
        "dataEmissao": "2018-07-26 00:00:00.0"
    }
]
    ```
