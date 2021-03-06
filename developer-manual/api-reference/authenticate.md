# 公共请求参数

## 公共请求头参数

公共请求参数是指每个接口都需要使用到的请求参数。如下表所示的参数均放在HTTP请求的头部。

| 参数 | 类型 | 说明 |
| :--- | :--- | :--- |
| Authorization | string | 接口请求所需的认证码，即Token，您可以在GrowingIO平台的项目配置中获取一个长期有效的Token，获取方法请参考[API Token管理](https://app.gitbook.com/@growingio/s/v3/product-manual/projectmange/projectmange/api-token)。 |

## 其他常用参数

下表参数为您在请求时常用的参数。

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#x53C2;&#x6570;</th>
      <th style="text-align:left">&#x7C7B;&#x578B;</th>
      <th style="text-align:left">&#x8BF4;&#x660E;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">project_uid</td>
      <td style="text-align:left">string</td>
      <td style="text-align:left">
        <p>&#x9879;&#x76EE;UID&#x3002;</p>
        <p>&#x767B;&#x5F55;GrowingIO&#x5E73;&#x53F0;&#xFF0C;&#x9009;&#x62E9;&#x5BF9;&#x5E94;&#x7684;&#x9879;&#x76EE;&#x540E;&#xFF0C;&#x9875;&#x9762;
          URL&#x4E2D;projects&#x540E;&#x7684;&#x503C;&#x3002;</p>
        <p><b>&#x83B7;&#x53D6;&#x793A;&#x4F8B;</b>&#xFF1A;</p>
        <p>&#x9009;&#x62E9;&#x9879;&#x76EE;&#x540E;&#x9875;&#x9762;URL&#x4E3A;<code>https://www.growingio.com/admin/projects/nxog09md/dashboard</code>&#x5F53;&#x524D;&#x9879;&#x76EE;&#x7684;UID&#x4E3A;<code>nxog09md</code>&#x3002;&#x8BE6;&#x7EC6;&#x8BF7;&#x53C2;&#x8003;
          <a
          href="../../product-manual/projectmange/projectmange/get-uid.md">&#x83B7;&#x53D6;&#x9879;&#x76EE;UID</a>&#x3002;</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#x9879;&#x76EE; ID</td>
      <td style="text-align:left">string</td>
      <td style="text-align:left">GrowingIO&#x5206;&#x914D;&#x7684;&#x9879;&#x76EE;ID&#x3002;&#x83B7;&#x53D6;&#x65B9;&#x5F0F;&#x8BF7;&#x53C2;&#x8003;&#x9879;&#x76EE;&#x516C;&#x94A5;&#x7684;&#x83B7;&#x53D6;&#x65B9;&#x5F0F;&#x3002;</td>
    </tr>
  </tbody>
</table>

