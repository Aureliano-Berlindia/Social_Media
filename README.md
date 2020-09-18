# Instagram 爬取指定用户所有POST

---
📖使用方法：

1. 相关库安装：[IgramScraper](https://github.com/realsirjoe/instagram-scraper), tqdm(进度条)

2. 在`instagram.with_credentials('user','pass')`填写用户名&密码

3. 爬取指定帐号所有post使用[XXX-igscraper](https://github.com/Aureliano-Berlindia/Social_Media/blob/master/XXX-igscraper.ipynb)

4. 根据Tags爬取Post和用户信息使用[Get_media_tags](https://github.com/Aureliano-Berlindia/Social_Media/blob/master/Get%20media%20by%20tag.ipynb)

---
⚠注意事项：
1. 大陆网路请使用**VPN**后运行，非大陆网路可不用设置Proxies

2. `get_medias('username',99999)`为**一次**爬取，无需担心频率

3. 根据`media_id`爬取帐号信息时每个帐号为一次爬取，请**设置适当频率**防止封号
