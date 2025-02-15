---

copyright:
 years: 2015, 2016

---

{:new_window: target="_blank"}
# 配置音效、有效負載以及 iOS 徽章

{: #badge-sound-payload}

配置 iOS 徽章、音效及其他 JSON 有效負載。

1. 在 Push Notifications 儀表板上，移至**通知**標籤。
2. 移至**選用欄位**區段，以配置下列推送通知特性。a. **iOS 徽章** - 對於 iOS 裝置，這是顯示為應用程式圖示徽章的號碼。如果沒有此內容，則不會變更徽章。若要移除徽章，請將此內容的值設為 0。

	b. **音效檔** - 輸入指向行動式應用程式中音效檔的字串。在有效負載中，指定要使用之音效檔的字串名稱。


	Android

	```
	"settings":{
	     "gcm":{
	     "sound":"tt.wav",
	  }
	 }  
	```

	iOS

	```
	"settings": {
	     "apns" : {
	      "badge": 10,
	      "sound": "tt.wav",
	  }
	}
	``` 		
**其他有效負載** - 此有效負載可以是任意鍵值組，而且必須是您要與推送通知一起傳送的 JSON 物件。

	```
	{"key":"value", "key2":"value2"}
	```
