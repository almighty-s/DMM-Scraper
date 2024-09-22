orginal

https://github.com/stashapp/CommunityScrapers/blob/master/scrapers/DMM.yml

20240921

original版がうまく動かなかったので、色々修正。

・sceneSearch: で Title: の取得方法を変更

・sceneScraper: で Title: Details: の取得方法を変更

・sceneByFragment: で queryURL: に除外キーワードを追加
                   で queryURLReplace: を変更

・sceneByName: で queryURL: queryURLReplace: を変更

・sceneSearch: を変更

・sceneQueryScraper: を変更

・performerByURL: performerByName: を追加

・performerSearch: performerScraper: を追加


できるようになったこと

・Scenes → Tagger で正常にScrapeできるようになった

・Scene → Edit → Scrape Query でScrapeできるようなった

・Scene → Edit → URLs でScrapeできるようになった

・Performers → Edit → URL でScrapeできるようになった。


まだできないこと
・Scene → Edit → Scrape with... で検索できない
  多分ファイル名になってる品番が正しく渡されてない気がする。

・Performers → Edit → Scrape with... で検索結果はでるが、Scrapeできない。


memo
FANZA動画からScrapeしてるバージョン

https://git.feederbox.cc/Gykes/DMM-Scraper/src/branch/main/DMM.yml
