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
        + code: success (string)
        + result (object)
            + bukken (object)
            + article (array)
            	+ (object)
            + menu (array)
            	+ (object)
            + carousel (array)
                + (object)
                    + id: 112 (number)
                    + message: ご好評につき事前案内会追加開催！ (string)
                    + submessage: 再開発で生まれ変わった「保谷」に誕生する</br>英国郊外のマナーハウスを彷彿とさせるレジデンス。</br>「ヴェレーナ保谷」にどうぞご期待下さい。 (string)
                    + image_url: /external/images/152/pict20190426172848.png (string)
                    + link_url: https://www.meiwajisyo.co.jp/lp/yokohamasalon/ (string)
                    + button_text: 来場予約はこちら (string)
                    + created_at: `2020-12-01 09:58:42` (string)
                    + updated_at: `2020-12-01 09:58:42` (string)
                + (object)
                    + id: 133 (number)
                    + message: ＳＮＳプレゼントキャンペーン開催</br>2020年11月まで、お早めに！ (string)
                    + submessage: (string, nullable)
                    + image_url: /external/images/152/pict20190426172848.png (string)
                    + link_url: https://www.meiwajisyo.co.jp/lp/yokohamasalon/ (string)
                    + button_text: 詳細はこちら (string)
                    + created_at: `2020-11-01 09:58:42` (string)
                    + updated_at: `2020-11-01 09:58:42` (string)
            + footer (array)
            	+ (object)
            + osusume (array)
            + hasOsusume: false (boolean)
            + privacy_policies (array)
            	+ (object)

