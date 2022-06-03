## 数据集
[训练数据](https://pan.baidu.com/s/1BBWLsiA-xVIQcFD7gOjEMw?pwd=p8db)  提取码: p8db

[验证数据](https://pan.baidu.com/s/13W-pj6KUOkcc7HG2LfUgDQ?pwd=45tw)  提取码: 45tw

[测试集](https://pan.baidu.com/s/1eZuFvdvuVB8LrAFUbHulPw?pwd=elui)  提取码: elui

[已训练模型文件: best checkpoint](https://pan.baidu.com/s/1Hb2Kujr_vjp-hWQGcIUotw?pwd=6a7j) 提取码: 6a7j

## 验证集上效果 所有分类标签的准确度

|tag-name|class|accuracy|
|:----|:----:|----:|
|location_traffic_convenience|-2|0.9779578447341919|
|location_traffic_convenience|-1|0.9644047021865845|
|location_traffic_convenience|0|0.8011305332183838|
|location_traffic_convenience|1|0.9782257080078125|
|location_distance_from_business_district|-2|0.9324278831481934|
|location_distance_from_business_district|-1|0.9469572305679321|
|location_distance_from_business_district|0|0.7274891138076782|
|location_distance_from_business_district|1|0.9366507530212402|
|location_easy_to_find|-2|0.9660308957099915|
|location_easy_to_find|-1|0.977387547492981|
|location_easy_to_find|0|0.8485990166664124|
|location_easy_to_find|1|0.965814471244812|
|service_wait_time|-2|0.9256792068481445|
|service_wait_time|-1|0.9621228575706482|
|service_wait_time|0|0.8822683691978455|
|service_wait_time|1|0.8854168653488159|
|service_waiters_attitude|-2|0.9720575213432312|
|service_waiters_attitude|-1|0.9732229709625244|
|service_waiters_attitude|0|0.9064614176750183|
|service_waiters_attitude|1|0.9738591909408569|
|service_parking_convenience|-2|0.9665371775627136|
|service_parking_convenience|-1|0.9770861864089966|
|service_parking_convenience|0|0.9461905360221863|
|service_parking_convenience|1|0.9585880041122437|
|service_serving_speed|-2|0.96295166015625|
|service_serving_speed|-1|0.9725004434585571|
|service_serving_speed|0|0.9076807498931885|
|service_serving_speed|1|0.9602636694908142|
|price_level|-2|0.9541576504707336|
|price_level|-1|0.9700474739074707|
|price_level|0|0.9037930369377136|
|price_level|1|0.9291220903396606|
|price_cost_effective|-2|0.9362762570381165|
|price_cost_effective|-1|0.9551070332527161|
|price_cost_effective|0|0.8604820370674133|
|price_cost_effective|1|0.9471837878227234|
|price_discount|-2|0.96500164270401|
|price_discount|-1|0.8470784425735474|
|price_discount|0|0.9222396016120911|
|price_discount|1|0.9537778496742249|
|environment_decoration|-2|0.9657709002494812|
|environment_decoration|-1|0.9509904980659485|
|environment_decoration|0|0.9085783958435059|
|environment_decoration|1|0.9618033170700073|
|environment_noise|-2|0.9407381415367126|
|environment_noise|-1|0.9702510237693787|
|environment_noise|0|0.9073789715766907|
|environment_noise|1|0.9409195184707642|
|environment_space|-2|0.9394290447235107|
|environment_space|-1|0.9721270799636841|
|environment_space|0|0.9252169132232666|
|environment_space|1|0.9455726146697998|
|environment_cleaness|-2|0.9491977691650391|
|environment_cleaness|-1|0.9618091583251953|
|environment_cleaness|0|0.9075682163238525|
|environment_cleaness|1|0.9542970061302185|
|dish_portion|-2|0.9304572343826294|
|dish_portion|-1|0.9549482464790344|
|dish_portion|0|0.8621771335601807|
|dish_portion|1|0.9321153163909912|
|dish_taste|-2|0.9320720434188843|
|dish_taste|-1|0.9683513045310974|
|dish_taste|0|0.8908829689025879|
|dish_taste|1|0.9080910086631775|
|dish_look|-2|0.8589658141136169|
|dish_look|-1|0.9120063781738281|
|dish_look|0|0.7616218328475952|
|dish_look|1|0.8826581835746765|
|dish_recommendation|-2|0.9183738231658936|
|dish_recommendation|-1|0.9411727786064148|
|dish_recommendation|0|0.8723265528678894|
|dish_recommendation|1|0.925330638885498|
|others_overall_experience|-2|0.5932890772819519|
|others_overall_experience|-1|0.9791519045829773|
|others_overall_experience|0|0.8673533201217651|
|others_overall_experience|1|0.913596510887146|
|others_willing_to_consume_again|-2|0.9407825469970703|
|others_willing_to_consume_again|-1|0.9790936708450317|
|others_willing_to_consume_again|0|0.8699713349342346|
|others_willing_to_consume_again|1|0.9430780410766602|


## 分类报告
|tag-name|class|precision|recall|f1-score|support|
|:----|:----:|:----|:----|:----|:----|
|location_traffic_convenience|-2|0.97|0.97|0.97|11757|
|location_traffic_convenience|-1|0.77|0.32|0.46|182|
|location_traffic_convenience|0|0.00|0.00|0.00|136|
|location_traffic_convenience|1|0.89|0.91|0.90|2925|
|location_distance_from_business_district|-2|0.94|0.93|0.93|12032|
|location_distance_from_business_district|-1|0.00|0.00|0.00|90|
|location_distance_from_business_district|0|0.00|0.00|0.00|80|
|location_distance_from_business_district|1|0.72|0.76|0.74|2798|
|location_easy_to_find|-2|0.96|0.96|0.96|11516|
|location_easy_to_find|-1|0.69|0.72|0.71|552|
|location_easy_to_find|0|0.00|0.00|0.00|329|
|location_easy_to_find|1|0.86|0.84|0.85|2603|
|service_wait_time|-2|0.97|0.96|0.97|13237|
|service_wait_time|-1|0.68|0.28|0.40|465|
|service_wait_time|0|0.28|0.03|0.06|599|
|service_wait_time|1|0.54|0.12|0.20|699|
|service_waiters_attitude|-2|0.91|0.88|0.89|5992|
|service_waiters_attitude|-1|0.76|0.75|0.76|1209|
|service_waiters_attitude|0|0.67|0.46|0.55|1830|
|service_waiters_attitude|1|0.91|0.91|0.91|5969|
|service_parking_convenience|-2|0.99|1.00|0.99|14046|
|service_parking_convenience|-1|0.54|0.11|0.19|188|
|service_parking_convenience|0|0.33|0.00|0.01|204|
|service_parking_convenience|1|0.66|0.73|0.70|562|
|service_serving_speed|-2|0.97|0.97|0.97|12677|
|service_serving_speed|-1|0.74|0.77|0.75|805|
|service_serving_speed|0|0.00|0.00|0.00|368|
|service_serving_speed|1|0.80|0.80|0.80|1150|
|price_level|-2|0.92|0.87|0.89|7497|
|price_level|-1|0.81|0.80|0.81|1760|
|price_level|0|0.71|0.66|0.68|3515|
|price_level|1|0.71|0.65|0.68|2228|
|price_cost_effective|-2|0.94|0.93|0.93|11428|
|price_cost_effective|-1|0.70|0.43|0.53|445|
|price_cost_effective|0|0.52|0.09|0.16|398|
|price_cost_effective|1|0.75|0.78|0.76|2729|
|price_discount|-2|0.95|0.91|0.93|9262|
|price_discount|-1|0.00|0.00|0.00|266|
|price_discount|0|0.66|0.64|0.65|2631|
|price_discount|1|0.79|0.75|0.77|2841|
|environment_decoration|-2|0.93|0.90|0.91|7801|
|environment_decoration|-1|0.74|0.12|0.21|275|
|environment_decoration|0|0.70|0.46|0.55|1312|
|environment_decoration|1|0.86|0.90|0.88|5612|
|environment_noise|-2|0.92|0.92|0.92|10521|
|environment_noise|-1|0.81|0.69|0.74|481|
|environment_noise|0|0.71|0.42|0.53|665|
|environment_noise|1|0.77|0.77|0.77|3333|
|environment_space|-2|0.92|0.88|0.90|9491|
|environment_space|-1|0.71|0.69|0.70|774|
|environment_space|0|0.67|0.55|0.60|1310|
|environment_space|1|0.78|0.79|0.78|3425|
|environment_cleaness|-2|0.92|0.91|0.92|9596|
|environment_cleaness|-1|0.70|0.57|0.63|625|
|environment_cleaness|0|0.64|0.38|0.47|627|
|environment_cleaness|1|0.82|0.84|0.83|4152|
|dish_portion|-2|0.89|0.84|0.86|8112|
|dish_portion|-1|0.72|0.69|0.71|1442|
|dish_portion|0|0.60|0.18|0.27|1405|
|dish_portion|1|0.79|0.79|0.79|4041|
|dish_taste|-2|0.83|0.42|0.55|756|
|dish_taste|-1|0.71|0.56|0.63|580|
|dish_taste|0|0.75|0.79|0.77|5820|
|dish_taste|1|0.84|0.83|0.83|7844|
|dish_look|-2|0.86|0.91|0.8810758|
|dish_look|-1|0.58|0.11|0.19|455|
|dish_look|0|0.00|0.00|0.00|661|
|dish_look|1|0.70|0.59|0.64|3126|
|dish_recommendation|-2|0.93|0.96|0.9412083|
|dish_recommendation|-1|0.67|0.41|0.51|335|
|dish_recommendation|0|1.00|0.01|0.01|287|
|dish_recommendation|1|0.79|0.69|0.74|2295|
|others_overall_experience|-2|0.00|0.00|0.00|285|
|others_overall_experience|-1|0.81|0.75|0.78|1283|
|others_overall_experience|0|0.66|0.53|0.59|3357|
|others_overall_experience|1|0.88|0.92|0.9010075|
|others_willing_to_consume_again|-2|0.90|0.90|0.90|9354|
|others_willing_to_consume_again|-1|0.72|0.72|0.72|577|
|others_willing_to_consume_again|0|0.67|0.01|0.01|395|
|others_willing_to_consume_again|1|0.83|0.81|0.82|4674|


accuracy: 0.9345

|classification reporter |precision|recall|f1-score|support|
|----|----|----|----|----|
|micro-avg|0.88|0.85|0.87|300000|
|macro-avg|0.70|0.59|0.61|300000|
|weighted-avg|0.87|0.85|0.86|300000|
|samples-avg|0.88|0.85|0.87|300000|


