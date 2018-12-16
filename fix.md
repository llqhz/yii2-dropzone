1 修改 autoDectet = false 并重新发布资源
2 修改dropzone包的removeaction 第29行 （yii命名空间加上\）
Yii::$app->response->format=yii\web\Response::FORMAT_JSON;
=》 Yii::$app->response->format=\yii\web\Response::FORMAT_JSON;
