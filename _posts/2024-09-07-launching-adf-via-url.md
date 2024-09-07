---
layout: post
title: "Launching ADF via URL: Navigate Like a Pro in Microsoft Edge"
date: 2024-09-07
categories: [Azure Data Factory, Productivity, Microsoft Edge]
tags: [ADF, URL, Azure, Edge Browser]
---

## Launching ADF via URL: Navigate Like a Pro in Microsoft Edge

Alright, data wranglers! Let's talk about something that’ll save you a few precious clicks and boost your productivity—**launching Azure Data Factory (ADF) directly from your browser using URLs**. Specifically, we’re going to use Microsoft Edge, but this works just as well in other browsers too.

Instead of fumbling through the Azure portal every time you want to jump into ADF, **bookmarking specific URLs** can make navigating through your pipelines a breeze. Ready? Let’s dive in.

### The General ADF URL Format

The beauty of ADF is that it’s URL-driven. That means you can construct URLs for different parts of your Data Factory and save yourself the hassle of manual navigation. Here’s the basic structure:

```
https://adf.azure.com/environments/<environment-name>/dataFactories/<data-factory-name>/
```

Let’s break that down:

- `<environment-name>`: The Azure environment (usually `prod`, `test`, etc.).
- `<data-factory-name>`: The name of your Data Factory.

### Example: Accessing Your Data Factory Dashboard

Say you’ve got a Data Factory named `myDataFactory` in your `prod` environment. Here’s how the URL looks:
```
https://adf.azure.com/environments/prod/dataFactories/myDataFactory/
```

Copy and paste that URL into Edge (or your preferred browser), and you’ll jump straight into your ADF dashboard—no portal navigation required.

### Going Deeper: Directly Accessing a Specific Pipeline

Want to go straight to a specific pipeline without wading through menus? You can append `/edit/<pipeline-name>` to your URL. Here's an example:

```
https://adf.azure.com/environments/prod/dataFactories/myDataFactory/edit/myPipeline
```

This takes you straight to the **Pipelines** section of your Data Factory, where you can view, edit, and create new pipelines.

### Bookmark Your Way to Efficiency

One of the best things you can do to streamline your ADF work is to **bookmark** these URLs. Whether you’re accessing the Data Factory dashboard, a specific pipeline, or the entire list of pipelines, just hit that bookmark button in Edge (or any browser) to save these shortcuts.

You can even organize your bookmarks into folders—one for each Data Factory environment, for example—to keep things tidy. Imagine never having to manually navigate through the portal again!

### Bonus: Pin Tabs in Edge

Microsoft Edge lets you pin tabs, which means you can keep your most frequently used ADF URLs open and ready to go. Here's how to do it:

1. Open the URL you want to pin in Edge.
2. Right-click the tab.
3. Select **Pin**.

Your pinned tab will shrink to an icon and stay at the top of your browser, so it’s always there when you need it.

### Full Example

Let’s walk through a full example with a fake environment and Data Factory.

1. **Access the Data Factory dashboard**:
    ```plaintext
    https://adf.azure.com/environments/prod/dataFactories/myAwesomeDataFactory/
    ```

2. **Jump to editing a pipeline**:
    ```plaintext
    https://adf.azure.com/environments/prod/dataFactories/myAwesomeDataFactory/edit/transformPipeline
    ```

3. **View all pipelines**:
    ```plaintext
    https://adf.azure.com/environments/prod/dataFactories/myAwesomeDataFactory/pipelines
    ```

### Final Thoughts

And that’s it! By using direct URLs in Microsoft Edge (or any browser), you can access ADF way faster than navigating through the Azure portal each time. Whether you're diving into a specific pipeline or just checking the dashboard, these URLs will save you time and make managing ADF a whole lot easier.

---

If you found this helpful and want more time-saving tips, feel free to reach out at [jason@jasonhorner.com](mailto:jason@jasonhorner.com) or connect with me on Twitter [@jasonhorner](https://twitter.com/jasonhorner). And hey, if you need consulting on **data platform** or **AI projects**, I’m available to help get your next big idea off the ground!

