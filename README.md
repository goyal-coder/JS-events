# JavaScript Events

## 1️⃣ Mouse Events 🖱️
```js
onclick        // Triggered when an element is clicked.
ondblclick     // Fires when an element is double-clicked.
onmousedown    // Fires when the mouse button is pressed down.
onmouseup      // Fires when the mouse button is released.
onmouseover    // Triggered when the mouse moves over an element.
onmouseout     // Triggered when the mouse leaves an element.
onmousemove    // Fires continuously as the mouse moves.
```

## 2️⃣ Keyboard Events ⌨️
```js
onkeydown   // Fires when a key is pressed down.
onkeypress  // Fires when a key is pressed and held (deprecated).
onkeyup     // Fires when a key is released.
```

## 3️⃣ Form Events 📝
```js
onchange    // Fires when an input element's value changes.
onfocus     // Fires when an input element gets focus.
onblur      // Fires when an input element loses focus.
oninput     // Fires when an input value is being entered.
onsubmit    // Fires when a form is submitted.
onreset     // Fires when a form is reset.
```

## 4️⃣ Clipboard Events 📋
```js
oncopy   // When content is copied
oncut    // When content is cut
onpaste  // When content is pasted
```

## 5️⃣ Drag & Drop Events 🖱️➡️
```js
ondrag        // When an element is dragged
ondragstart   // When dragging starts
ondragend     // When dragging ends
ondragenter   // When a dragged item enters a drop zone
ondragleave   // When a dragged item leaves a drop zone
ondragover    // When a dragged item is over a drop zone
ondrop        // When a dragged item is dropped
```

## 6️⃣ Touch Events (For Mobile Devices) 📱
```js
ontouchstart  // When a touch starts
ontouchmove   // When a finger moves on the screen
ontouchend    // When a touch ends
ontouchcancel // When a touch is interrupted
```

## 7️⃣ Pointer Events (For Mouse, Touch, and Stylus) 🎨
```js
onpointerdown   // When a pointer is pressed
onpointerup     // When a pointer is released
onpointermove   // When a pointer moves
onpointerenter  // When a pointer enters an element
onpointerleave  // When a pointer leaves an element
onpointercancel // When the pointer is canceled
```

## 8️⃣ Focus Events 🔍
```js
onfocus      // When an element gets focus
onblur       // When an element loses focus
onfocusin    // When focus is moved to an element
onfocusout   // When focus is moved away from an element
```

## 9️⃣ Media Events 🎵📹
```js
onplay         // When media starts playing
onpause        // When media is paused
onended        // When media playback ends
onvolumechange // When volume is changed
onseeked       // When seeking is complete
onseeking      // When seeking starts
onratechange   // When playback speed changes
ontimeupdate   // When media playback time updates
```

## 🔟 Animation & Transition Events 🎞️
```js
onanimationstart    // When a CSS animation starts
onanimationend      // When a CSS animation ends
onanimationiteration // When a CSS animation repeats
ontransitionend     // When a CSS transition finishes
```

## 1️⃣1️⃣ Speech Recognition Events (Web Speech API) 🎙️
```js
onspeechstart  // When speech recognition starts
onspeechend    // When speech recognition ends
onresult       // When speech recognition detects speech
```

## 1️⃣2️⃣ Page Load & Visibility Events 🌐
```js
onload             // When a page or image loads
onunload           // When a page is unloading
onbeforeunload     // Before a page unloads (used for warnings)
onresize           // When the browser window resizes
onscroll           // When scrolling occurs
onhashchange       // When the URL hash changes
onpopstate         // When the browser history changes
onvisibilitychange // When page visibility changes (e.g., when switching tabs)
```

## 1️⃣3️⃣ Server-Sent Events (SSE) & WebSockets 🌐
```js
onmessage  // When a message is received from a server
onopen     // When a WebSocket connection is opened
onclose    // When a WebSocket connection is closed
onerror    // When a WebSocket encounters an error
```

## 1️⃣4️⃣ Custom Events 🛠️
```js
CustomEvent   // You can create your own events using new CustomEvent("myEvent")
.dispatchEvent()  // Used to dispatch a custom event
```

✅ **This is the ULTIMATE list of JavaScript events!**
