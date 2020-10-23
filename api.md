FORMAT: 1A
## ユーザ情報取得 [/v1/product/top{?appMasterId,userId,deviceId,productId}]

### 物件トップ取得API [GET]

#### 処理概要

* 物件トップで表示する情報を取得する。
* このAPIでプレミアムPushの表示情報も返却する。 

+ Parameters

    + appMasterId: 2 (number, required) - アプリID
    + userId: 1010245 (number, required) - ユーザーID
    + deviceId: 309 (number, required) - 端末ID
    + productId: 2053 (number, required) - 物件ID 

+ Response 200 (application/json)

    + Attributes
        + code: success (string, required)
        + result (object, required)
            + bukken (object, required)
            + article (array)
            	+ (object)
            + menu (array)
            	+ (object)
            + footer (array)
            	+ (object)
            + osusume (array)
            + hasOsusume: false (boolean, required)
            + privacy_policies (array)
            	+ (object)
