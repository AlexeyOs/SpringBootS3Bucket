#SpringBootS3Bucket

## Данный модуль является модификацие простого примера для работы с корзиной(bucket) сервиса amazone S3. Оригинальная статься [здесь](https://medium.com/oril/uploading-files-to-aws-s3-bucket-using-spring-boot-483fcb6f8646)

Для того, чтобы запустить данный пример, вам придется создать свою корзину(bucket). Как это сделать
описано в оргинальной [статье: ](https://medium.com/oril/uploading-files-to-aws-s3-bucket-using-spring-boot-483fcb6f8646) https://medium.com/oril/uploading-files-to-aws-s3-bucket-using-spring-boot-483fcb6f8646
Корзина может быть публичной или приватной. Параметр публичного или приватного хранилища настраивается в [AmazonClient.java](src/main/java/com/example/bucket/service/AmazonClient.java) классе, метод `uploadFileTos3bucket()` свойство `CannedAccessControlList.Private`

