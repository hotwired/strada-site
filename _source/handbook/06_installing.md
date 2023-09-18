---
permalink: /handbook/installing.html
description: "Learn how to install Strada in your application."
---

# Installing Strada in Your Application

Strada can either be referenced in compiled form via the Strada distributable script directly in the `<head>` of your application or through npm via a bundler like esbuild.

## As An npm Package

You can install Strada from npm via the `npm` or `yarn` packaging tools. Then require or import that in your code:

```javascript
import * as Strada from "@hotwired/strada"
```
