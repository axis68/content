---
title: WindowEventHandlers
slug: Web/API/WindowEventHandlers
tags:
  - API
  - HTML-DOM
  - Interface
  - Mixin
  - Reference
  - WindowEventHandlers
browser-compat: api.WindowEventHandlers
---
{{APIRef("HTML DOM")}}

The **`WindowEventHandlers`** mixin describes the event handlers common to several interfaces like {{domxref("Window")}}, or {{domxref("HTMLBodyElement")}} and {{domxref("HTMLFrameSetElement")}}. Each of these interfaces can implement additional specific event handlers.

> **Note:** `WindowEventHandlers` is a mixin and not an interface; you can't actually create an object of type `WindowEventHandlers`.

## Properties

_The events properties, of the form `onXYZ`, are defined on the {{domxref("WindowEventHandlers")}}, and implemented by {{domxref("Window")}}, and {{domxref("WorkerGlobalScope")}} for Web Workers._

- {{domxref("WindowEventHandlers.onbeforeunload")}}
  - : Is an [event handler](/en-US/docs/Web/Events/Event_handlers) representing the code to be called when the {{domxref("Window.beforeunload_event", "beforeunload")}} event is raised.
- {{domxref("WindowEventHandlers.onrejectionhandled")}}
  - : Is an [event handler](/en-US/docs/Web/Events/Event_handlers) representing the code to be called when the {{event("rejectionhandled")}} event is raised, indicating that a {{jsxref("Promise")}} was rejected and the rejection has been handled.
- {{domxref("WindowEventHandlers.onunhandledrejection")}}
  - : Is an [event handler](/en-US/docs/Web/Events/Event_handlers) representing the code to be called when the {{domxref("Window.unhandledrejection_event", "unhandledrejection")}} event is raised, indicating that a {{jsxref("Promise")}} was rejected but the rejection was not handled.
- {{domxref("WindowEventHandlers.onunload")}}
  - : Is an [event handler](/en-US/docs/Web/Events/Event_handlers) representing the code to be called when the {{event("unload")}} event is raised.

## Methods

_This interface defines no method._

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{domxref("Window")}} and {{domxref("WorkerGlobalScope")}}
