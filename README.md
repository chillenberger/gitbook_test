---
description: This is some writing!
---

# Page

## A <mark style="color:blue;">big header</mark>

Test links [#test](./#test "mention") lets take a look. [page-1.md](page-1.md "mention") hmmm.

{% @dan_test_1/dan_test_1 content="**bolded** 

> "No human ever steps in the same river twice, for it’s not the same river and they are not the same human." — _Heraclitus_

## header

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

### Table

|   |   |   |
| - | - | - |
|   |   |   |
|   |   |   |
|   |   |   |
" %}

{% @dan_test_1/dan_test_1 content="Replace default content" %}



<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td></td><td>card 1</td><td></td></tr><tr><td></td><td>card 2</td><td></td></tr></tbody></table>

{% @dan_test_1/dan_test_1 content="Click mroe stuff" %}

{% hint style="info" %}
test
{% endhint %}

A paragraph with a link to [Page 1](page-1.md).  But this link goes to [Header level 2 in page 1](page-1.md#a-level-2-header)

<details>

<summary>test</summary>

test

more

even more



</details>



{% code title="Test name for html" lineNumbers="true" %}
```html
<div>
    This is a div
    <a>link in code</a>
</div>
```
{% endcode %}

{% content-ref url="page-1.md" %}
[page-1.md](page-1.md)
{% endcontent-ref %}

{% tabs %}
{% tab title="First Tab" %}
Tab 1
{% endtab %}

{% tab title="Second Tab" %}
Tab 2
{% endtab %}

{% tab title="Untitled" %}
Tab 3
{% endtab %}
{% endtabs %}



{% file src=".gitbook/assets/test.txt" %}
