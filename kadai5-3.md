## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* 住所を入力すると都道府県、市、町などが検索され表示される
* リクエストとレスポンスのフォーマット
* https://zipcloud.ibsnet.co.jp/api/search
* {
	"message": null,
	"results": [
		{
			"address1": "北海道",
			"address2": "美唄市",
			"address3": "上美唄町協和",
			"kana1": "ﾎｯｶｲﾄﾞｳ",
			"kana2": "ﾋﾞﾊﾞｲｼ",
			"kana3": "ｶﾐﾋﾞﾊﾞｲﾁｮｳｷｮｳﾜ",
			"prefcode": "1",
			"zipcode": "0790177"
		},
		{
			"address1": "北海道",
			"address2": "美唄市",
			"address3": "上美唄町南",
			"kana1": "ﾎｯｶｲﾄﾞｳ",
			"kana2": "ﾋﾞﾊﾞｲｼ",
			"kana3": "ｶﾐﾋﾞﾊﾞｲﾁｮｳﾐﾅﾐ",
			"prefcode": "1",
			"zipcode": "0790177"
		}
	],
	"status": 200
}
	
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* Free Dictionary API
* https://dictionaryapi.dev/
* エンドポイントと機能
* https://api.dictionaryapi.dev/api/v2/entries/en/{word}
* 英単語の意味などを表示してくれる
* リクエストとレスポンスのフォーマット
* get https://api.dictionaryapi.dev/api/v2/entries/en/
* hello   "Hello!" or an equivalent greeting.
### Q3-3. 感想
* 今回の課題で苦労したこと
* 演習を通して理解できたこと
* Web APIの利便性や課題など
