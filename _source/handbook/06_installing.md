---
permalink: /handbook/installing.html
description: "Learn how to install Strada in your application."
---

# Installing Strada in Your Application

Strada can either be referenced in compiled form via the Strada distributable script directly in the `<head>` of your application, or through npm via a bundler like esbuild.

## Prerequisite: Install Stimulus

Strada leverages [Stimulus](https://stimulus.hotwired.dev) and the core `BridgeComponent` class is an extension of a Stimulus `Controller`. You must have Stimulus installed in your web app before installing Strada. See the [Stimulus installation instructions](https://stimulus.hotwired.dev/handbook/installing).

## In Compiled Form

You can float on the latest release of Strada using a CDN bundler or import <a href="https://unpkg.com/@hotwired/strada/dist/strada.js">strada.js</a> using a `<script type="module">` tag.

## As An npm Package

You can install Strada from npm via the `npm` or `yarn` packaging tools. Then require or import that in your code:

```javascript
import "@hotwired/strada"
```

# Installing Strada in Your Native Apps

Dedicated installation instructions are provided for the [iOS](https://github.com/hotwired/strada-ios) and [Android](https://github.com/hotwired/strada-android) libraries in their GitHub repos.

<div class="landing-actions">
  <a class="landing-actions__item" href="https://github.com/hotwired/strada-ios">
    <div class="landing-actions__icon landing-actions__icon--github" aria-hidden="true"></div>
    hotwired/strada-ios
  </a>

  <a class="landing-actions__item" href="https://github.com/hotwired/strada-android">
    <div class="landing-actions__icon landing-actions__icon--github" aria-hidden="true"></div>
    hotwired/strada-android
  </a>
</div>
