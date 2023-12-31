# The Javascript API
## Learn how to get the most out of Corpus’ widget using its powerful Javascript API

The Corpus Chatbot Widget API. This powerful interface empowers users with direct control over the chatbot widget using JavaScript, offering a variety of features that enhance user interaction and streamline customer engagement.

Whether you're looking to programmatically manage the visibility of your chatbot, automate the submission of prompts, or present users with a contact form at just the right moment, the Corpus Chatbot Widget API provides the tools necessary for creating a tailored and efficient user experience.

In this document, we will delve into the common functionalities provided by the API, such as showing or hiding the widget on your webpage, initiating conversations with auto-submitted prompts, and triggering the contact form display, among other capabilities. Each feature is designed to give you and your users a seamless and integrated chatbot experience, customizable to your unique business needs.

Once you've [installed the Widget](./installation/README.md), the following methods are available:

## Installation

To display the widget on your web application, simply copy and paste the following code snippet before the closing tag on each page where you'd like the widget to be visible to site visitors.

```html
<script>
!function(n,c){var t=n.Corpus||function(){var n=arguments;try{t[n[0]](n)}catch(n){}};t.i=!1,t.js=function(n,t){var o=c.createElement("script"),n=(o.type="text/javascript",o.async=!0,o.src=n,c.getElementsByTagName("script")[0]);n.parentNode.insertBefore(o,n),o.onload=t||function(){}},t.load=function(n){t.id=n[1],t.i||t.js("https://corpus.gocdn.io/launcher.js?id="+n[1],function(){t.i=!0})},window.Corpus=t}(window,document);

// initialize
Corpus('load', 'XXXXXXXXXXXXXXXXXXXXX');
</script>
```

To initialize the widget with the launcher hidden, overriding the default settings, use:

```js
Corpus('load', 'XXXXXXXXXXXXXXXXXXXXX', 'hidden');
```

[[warning]]
\* Replace `XXXXXXXXXXXXXXXXXXXXX` in the code above with your Chatbot ID.
[[/warning]]

To initialize the widget with the launcher hidden, overriding the default settings, use:

```js
Corpus('load', 'XXXXXXXXXXXXXXXXXXXXX', 'hidden');
```

---

## Identify users

Identify the active user’s and assign your internal user’s id, name, email, and avatar, if known (all fields are optional).

\* When a user is identified, the lead-capture feature will be disabled.

```js
Corpus('identify', 'internal-id', {
  name: "John Doe",
  email: "john.doe@gmail.com",
  avatar: "full url to avatar image"
});
```

or

```js
Corpus('identify', {
  id: "internal-id", // your user identifier
  name: "John Doe",
  email: "john.doe@gmail.com",
  avatar: "full url to avatar image"
});
```

---

## Javascript API

By loading the widget JavaScript, you gain access to a widget JavaScript object that responds to several methods. These methods enable you to interact with the messenger window.

### Hide widget

This will hide the widget panel if it is open. It will not hide the widget launcher.

```js
Corpus('hide');
```

### Show widget

Options: `Corpus('show' [, screen [, prompt]] )`

This will show the widget panel.

```js
Corpus('show');
```

This will show the widget’s chat (skip home screen).

```js
Corpus('show', 'chat');
```

With a promot:

```js
Corpus('show', 'chat', 'How can I reset my password?');
```

This will show the widget’s contact form.

```js
Corpus('show', 'contact');
```

### Toggle visibility

This will toggle the widget panel.

```js
Corpus('show', 'toggle');
```

### Submit prompt

A shortcut for Corpus('show', 'chat', 'QUESTION');.

This will show the widget’s chat form and auto-submit a prompt by the user.

```js
Corpus('prompt', 'How can I reset my password?');
```

### Set theme

This method overrides your settings and lets you controls the widget light/dark theme display mode.

```js
Corpus('theme', 'system'); // use system theme
Corpus('theme', 'light');
Corpus('theme', 'dark');
```
