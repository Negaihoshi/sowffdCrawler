sowffdCrawler
=============

##Introduction
  這是一個簡單抓取慈善福利基金會名單的爬蟲。
  資料來源：http://sowffd.sfaa.gov.tw/CharityFunds/charity_recentNews.do

##Requirements

    BeautifulSoup ver.4+

##Usage

    Python sowffdGet.py

##Output

    data.json
    data2.json

##Data Sample

      {
        "許可日期文號": [
          {
            "0": "51.04.14"
          }, 
          {
            "1": "台內社字第80633號函"
          }
        ], 
        "基金總額": "82,292,653元整", 
        "法院登記日期文號": [
          {
            "0": "51.05.07"
          }, 
          {
            "1": "登記簿第12冊第1頁第163號"
          }
        ], 
        "服務項目": "一、關於兒童福利事項。\r\n二、關於青少年福利事項。\r\n三、關於老人福利事項。\r\n四、關於婦女福利事項。\r\n五、關於身心障礙者福利事項。\r\n六、辦理志願服務業務。 \r\n七、承辦政府社會服務業務。\r\n八、與其他機構合作，辦理社會服務工作。\r\n九、其他慈善事業及傳道心靈重建事項。 \r\n", 
        "聯絡電話": "(02)2597-4868", 
        "代碼": "A0001", 
        "名稱": "財團法人基督教芥菜種會", 
        "網址": "http://www.mustard.org.tw", 
        "業務聯絡人": "丁小姐", 
        "董事長": "林元生", 
        "地址": "台北市中山區雙城街49巷6之1號3樓"
      }

##Todo