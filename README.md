# Produktspesifikasjon "Havnedata"
Dette er et test prosjekt for generering av produktspesifikasjoner

Legg inn config.yml som under og kjør github action:
* Generer produktspesifikasjon
* Evt. legg inn egne kapittel 
* Publish produktspesifikasjon site
* se resultatet på https://github.com/larsingea/ps_havnedata

Eksempel config.yml
```yml config
metadataId: 041f1e6e-bdbc-4091-b48f-8a5990f3cc5b
ogc_feature_api: https://ogcapitest.kartverket.no/rest/services/havnedata3_0/collections
output_directory: produktspesifikasjon
product_slug: havnedata
```