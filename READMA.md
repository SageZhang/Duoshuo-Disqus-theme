## һ�����ڷ�disqus�Ķ�˵���css

## ʹ��˵��

* �����޸ı���embed.js������`<form method="post">` �ĳ� `<form id="commenthw" method="post">`
* ����
```javascript
this.el.find(".ds-comments-tab-" + a).html(this.el.hasClass("ds-narrow") ? '<span class="ds-service-icon ds-' + a + '"></span>' + i: (i ? '<span class="ds-highlight">' + i + "</span>": "0") + s[a][1])
```
�޸ĳ�
```javascript
this.el.find(".ds-comments-tab-" + a).html(this.el.hasClass("ds-narrow") ? '<span class="ds-service-icon ds-' + a + '"></span>' + i: (i ? '<span class="ds-highlight">' + i + "</span>": "0") + s[a][1])
```

OK!

����㻹�������Զ����޸ģ����Բ鿴�ҵ�js:<http://www.ihewro.com/duoshuo/embedhw4.js>

