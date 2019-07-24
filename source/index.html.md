---
title: API Reference Practice

language_tabs: # must be one of https://git.io/vQNgJ
  - php


toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# 介紹

Slate api doc 練習

This example API documentation page was created with [Slate](https://github.com/lord/slate). Feel free to edit it and use it as a base for your own API's documentation.

# 驗證

> To authorize, use this code:

```php
require 'kittn'

api = strtoupper(hash('SHA256', 'Practice'.'6666'.'yourkey'));
```

> Make sure to replace `yourkey` with your API key.

<aside class="notice">
notice here
</aside>

# APIs

## 確認權限

> The above command returns JSON structured like this:

```json
  {
    "rolename": "admin"
  }

```

回傳使用者權限名稱

### HTTP Request

`GET http://mimir-env.hk2qb94ebi.ap-northeast-1.elasticbeanstalk.com/checkpermission`


## 編輯器顯示


把傳送的網址塞入iframe

<aside class="warning">若無傳遞參數，會顯示錯誤</aside>

### HTTP Request

`GET http://mimir-env.hk2qb94ebi.ap-northeast-1.elasticbeanstalk.com/webgl`

### URL Parameters

Parameter | Description
--------- | -----------
url | webgl index.html 完整路徑

