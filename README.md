# Ogura_Hyakunin_Isshu_LinkedRDF
小倉百人一首のLinkedRDF

## 構成
@prefix OguraHyakuninIsshu: \<https://sparql.crssnky.xyz/OguraHyakuninIsshu/URIs/Ogura_Hyakunin_Isshu_schema.ttl#\>  

rdfs:Class=OguraHyakuninIsshu:Phrase  
以下全てにprefix"OguraHyakuninIsshu:"  
| No | 歌人 | 上の句 | 下の句 | 上の句（ひらがな） | 下の句（ひらがな） |   
| ---- | ---- | ---- | ---- | ---- | ---- |  
| Number | Poet | Upper Phrase | Lower Phrase | Upper Phrase(Kana) | Lower Phrase(Kana) |  
詳しくは[SchemaTTL](https://sparql.crssnky.xyz/Ogura_Hyakunin_Isshu_LinkedRDF/URIs/Ogura_Hyakunin_Isshu_schema.ttl)

## Data
nyoronjp様 [Ogura_Hyakunin_Isshu.csvリポジトリ](https://github.com/nyoronjp/Ogura_Hyakunin_Isshu.csv)