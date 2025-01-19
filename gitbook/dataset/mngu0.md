---
icon: hand-pointer
---

# Interactive blocks

In addition to the default Markdown you can write, GitBook has a number of out-of-the-box interactive blocks you can use. You can find interactive blocks by pressing `/` from within the editor.

<figure><img src="https://gitbookio.github.io/onboarding-template-images/interactive-hero.png" alt=""><figcaption></figcaption></figure>

### Tabs

{% tabs %}
{% tab title="First tab" %}
Each tab is like a mini page — it can contain multiple other blocks, of any type. So you can add code blocks, images, integration blocks and more to individual tabs in the same tab block.
{% endtab %}

{% tab title="Second tab" %}
Add images, embedded content, code blocks, and more.

```javascript
const handleFetchEvent = async (request, context) => {
    return new Response({message: "Hello World"});
};
```
{% endtab %}
{% endtabs %}

### Expandable sections

 work in progress...
