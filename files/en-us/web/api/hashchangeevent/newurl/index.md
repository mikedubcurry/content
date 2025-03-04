---
title: HashChangeEvent.newURL
slug: Web/API/HashChangeEvent/newURL
tags:
  - API
  - HashChangeEvent
  - Property
  - Reference
  - Web API
browser-compat: api.HashChangeEvent.newURL
---
{{APIRef("HTML DOM")}}

The **`newURL`** read-only property of the
{{domxref("HashChangeEvent")}} interface returns the new URL to which the window is
navigating.

## Value

A {{domxref("DOMString")}}.

## Examples

```js
window.addEventListener('hashchange', function(event) {
  console.log('Hash changed to ' + event.newURL);
});
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
