## Constants

<dl>
<dt><a href="#addLocaleData">addLocaleData</a></dt>
<dd><p>i18n.js</p>
<p>This will setup the i18n language files and locale data for your app.</p>
<p>  IMPORTANT: This file is used by the internal build
  script <code>extract-intl</code>, and must use CommonJS module syntax
  You CANNOT use import/export in this file.</p>
</dd>
</dl>

## Functions

<dl>
<dt><a href="#getDaysLeft">getDaysLeft(paidUntil)</a> ⇒ <code>int</code></dt>
<dd><p>Get difference in days</p>
</dd>
<dt><a href="#getUrlParameter">getUrlParameter(urlParam)</a></dt>
<dd><p>Get value of the query param</p>
</dd>
<dt><a href="#isValidUrl">isValidUrl(str)</a> ⇒ <code>boolean</code></dt>
<dd><p>Returns true if URL is valid</p>
</dd>
<dt><a href="#renderDaysLeft">renderDaysLeft(paidUntil)</a> ⇒ <code>string</code></dt>
<dd><p>Returns a string of the time left from paidUntil (used for render)</p>
</dd>
<dt><a href="#trimDomain">trimDomain(urlParam)</a> ⇒ <code>string</code></dt>
<dd><p>Returns only the domain name (removes https / http/ query params)</p>
</dd>
</dl>

<a name="addLocaleData"></a>

## addLocaleData
i18n.js

This will setup the i18n language files and locale data for your app.

  IMPORTANT: This file is used by the internal build
  script `extract-intl`, and must use CommonJS module syntax
  You CANNOT use import/export in this file.

**Kind**: global constant  
<a name="getDaysLeft"></a>

## getDaysLeft(paidUntil) ⇒ <code>int</code>
Get difference in days

**Kind**: global function  
**Returns**: <code>int</code> - expirationDate difference in days  

| Param | Type | Description |
| --- | --- | --- |
| paidUntil | <code>int</code> | account.paidUntil |

**Example**  
```js
getDaysLeft(userData.paidUntil)
```
<a name="getUrlParameter"></a>

## getUrlParameter(urlParam)
Get value of the query param

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| urlParam | <code>string</code> | query param key ex. window.location = http://google.com?name=gaconnector getUrlParameter('name') // -> returns 'gaconnector' |

<a name="isValidUrl"></a>

## isValidUrl(str) ⇒ <code>boolean</code>
Returns true if URL is valid

**Kind**: global function  

| Param | Type |
| --- | --- |
| str | <code>string</code> | 

<a name="renderDaysLeft"></a>

## renderDaysLeft(paidUntil) ⇒ <code>string</code>
Returns a string of the time left from paidUntil (used for render)

**Kind**: global function  
**Returns**: <code>string</code> - 'Expired' if expiration date < current date or 'number of days left'  

| Param | Type |
| --- | --- |
| paidUntil | <code>int</code> | 

<a name="trimDomain"></a>

## trimDomain(urlParam) ⇒ <code>string</code>
Returns only the domain name (removes https / http/ query params)

**Kind**: global function  
**Returns**: <code>string</code> - A good string  

| Param | Type |
| --- | --- |
| urlParam | <code>string</code> | 

**Example**  
```js
trimDomain('https://momentjs.com/') // returns 'momentjs.com'
```

