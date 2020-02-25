## Functions

<dl>
<dt><a href="#foo">foo(n)</a> ⇒ <code>string</code></dt>
<dd><p>This is a function.</p>
</dd>
<dt><a href="#protection">protection(cloak, dagger)</a> ⇒ <code>survival</code></dt>
<dd><p>A quite wonderful function.</p>
</dd>
</dl>

## Typedefs

<dl>
<dt><a href="#iterator">iterator</a> : <code>function</code></dt>
<dd><p>This callback &#39;ITERATOR&#39; is a function that will run for each item on the collection. Once the &#39;done&#39; cb is called, the current iteration will end</p>
</dd>
</dl>

<a name="foo"></a>

## foo(n) ⇒ <code>string</code>
This is a function.

**Kind**: global function  
**Returns**: <code>string</code> - A good string  

| Param | Type | Description |
| --- | --- | --- |
| n | <code>string</code> | A string param |

**Example**  
```js
foo('hello')
```
<a name="protection"></a>

## protection(cloak, dagger) ⇒ <code>survival</code>
A quite wonderful function.

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| cloak | <code>object</code> | Privacy gown |
| dagger | <code>object</code> | Security |

<a name="iterator"></a>

## iterator : <code>function</code>
This callback 'ITERATOR' is a function that will run for each item on the collection. Once the 'done' cb is called, the current iteration will end

**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
|  | <code>any</code> |  |
| index | <code>int</code> | current iteration index |
| done | <code>fn</code> | callback that will define when the current iteration is finished |


