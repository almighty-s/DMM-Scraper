orginal

https://github.com/stashapp/CommunityScrapers/blob/master/scrapers/mgstage.yml

20240922

original版がうまく動かなかったので、色々修正。

・sceneSearch: で 取得方法を変更

・sceneScraper: で Performers:Name: の取得方法を変更


できるようになったこと

・Scenes → Tagger で正常にScrapeできるようになった

・Scene → Edit → Scrape Query でScrapeできるようなった

・Scene → Edit → URLs でScrapeできるようになった


まだできないこと
・Scene → Edit → Scrape with... で検索できない
  多分ファイル名になってる品番が正しく渡されてない気がする。

・sceneScraper: で Performers:Name: が配信専用動画の一部でHTMLタグの構成が違う(名前にリンクの有り無し)から出演者名がうまく取得できない。
  なんとか両対応できないかなぁ。

  
memo
FANZA動画からScrapeしてるバージョン

https://git.feederbox.cc/Gykes/DMM-Scraper/src/branch/main/DMM.yml
