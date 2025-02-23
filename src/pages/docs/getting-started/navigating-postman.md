---
title: "Navigating Postman"
order: 3
page_id: "navigating_postman"
contextual_links:
  - type: section
    name: "Prerequisites"
  - type: link
    name: "Download and Install"
    url: "https://www.postman.com/downloads/"
  - type: section
    name: "Additional Resources"
  - type: subtitle
    name: "Videos"
  - type: link
    name: "Bootcamp | Postman Level Up"
    url: "https://youtu.be/cCruwkHi9o4"
  - type: link
    name: "History | Postman Level Up"
    url: "https://www.youtube.com/watch?v=9VBTKwUCsGw&list=PLM-7VG-sgbtC5tNXxd28cmePSa9BYwqeU&index=4"
  - type: section
    name: "Next Steps"
  - type: link
    name: "Sending your first request"
    url: "/docs/getting-started/sending-the-first-request/"

warning: false

---

Postman provides a variety of views and controls for managing your API projects. The Postman UI is made up of the following components:

[![Postman app](https://assets.postman.com/postman-docs/app-overview-v8.jpg)](https://assets.postman.com/postman-docs/app-overview-v8.jpg)

* The left sidebar provides access to your collections, APIs, environments, mock servers, monitors and request [history](#history).
* The header allows you to create workspaces, access reports, explore the public API network, search within Postman, view sync status and notifications, move and invite collaborators to workspaces, capture requests and cookies, access your settings, account, and Postman plan.
* The center area is where you build and work with requests.
* The status bar along the bottom allows you to show/hide the sidebar, [find and replace](#find-and-replace), and open the [console](/docs/sending-requests/troubleshooting-api-requests/) on the left. On the right you can launch the __Bootcamp__, collection runner, trash, two pane view, and access help resources.

[![Resizing panes](https://assets.postman.com/postman-docs/resizing-panes-v8.gif)](https://assets.postman.com/postman-docs/resizing-panes-v8.gif)

You can also drag to resize the panes in the Postman UI.

[![Resizing panes](https://assets.postman.com/postman-docs/panes-resized-v8.gif)](https://assets.postman.com/postman-docs/panes-resized-v8.gif)

On the right panel, you will see icons to view the documentation, comments, code and request info.

<img alt="Right panel icons" src="https://assets.postman.com/postman-docs/right-panel-view-v8.jpg" height="300px"/>

To open the documentation tab, select the request under your collection and click the Documentation icon<img alt="Mini docs icon" src="https://assets.postman.com/postman-docs/mini-docs-icon-v8.jpg" width="50px"/> on the right panel.

<img alt="Documentation icon" src="https://assets.postman.com/postman-docs/overview-documentations-v8.jpg"/>

Click __View complete collection documentation__ to open the documentation in a new tab.

<img alt="Overview Documentation" src="https://assets.postman.com/postman-docs/documentation-pane-v8.jpg" height="400px"/>

To publish a documentation for a collection, see [Publishing your documentation](docs/publishing-your-api/publishing-your-docs/).

To open the comments tab, select the request under your collection and click the Comments icon <img alt="Mini comments icon" src="https://assets.postman.com/postman-docs/mini-comments-icon-v8.jpg" width="30px"/> on the right panel. You can switch to comment mode to leave comments on a specific part of the request, including parameters, headers, body and tests.

[![Overview Comments](https://assets.postman.com/postman-docs/overview-comments-v8.jpg)](https://assets.postman.com/postman-docs/overview-comments-v8.jpg)

To learn more about comments, see [Commenting on collections](docs/collaborating-in-postman/commenting-on-collections/).

To open the code snippets tab, select the request under your collection and click the Code icon on the right panel. See more on [Generating code snippets](/docs/sending-requests/generate-code-snippets/).

<img alt="Code snippets Pane" src="https://assets.postman.com/postman-docs/code-snippet-pane-v8.jpg" height="350px"/>

You can declutter your workspace by collapsing panes. Use the buttons at the bottom-left to hide the sidebar and at the bottom-right to toggle between single and two pane view.

[![general layout](https://assets.postman.com/postman-docs/split-pane-view-v8.jpg)](https://assets.postman.com/postman-docs/split-pane-view-v8.jpg)

## Find and replace

You can search your Postman workspace by clicking __Find and Replace__ at the bottom-left of Postman—or using the keyboard shortcuts `Command + SHIFT + F` / `Control + SHIFT + F`.

Enter your search string and optionally choose which entities to return, entering replacement text if necessary.

![Find and replace](https://assets.postman.com/postman-docs/find-and-replace-tab-v8.jpg)

Postman will search tabs, collections, and variables. You can click directly from the search results to open an entity.

## History

You can access a history of the requests you've made in Postman via the __History__ tab on the left of Postman. If you're signed into a Postman account, your history will sync across devices.

<img alt="History Request" src="https://assets.postman.com/postman-docs/history-request-v8.jpg" height="400px"/>

Click a request to open it again. Click __+__ to save the request to a collection. Toggle __Save Responses__ to save request responses so that you can view what was returned by a request when you open it from your history.

The __View more actions__ menu allows you to save, monitor, document, or mock a request. Use the delete (trash icon) or __Clear all__ options to remove requests from your history. You can multi-select requests by pressing `Command` or `Control` and clicking the requests.

## Tabs

You can send requests in Postman by opening tabs—click __+__ in the center of the screen, or press `Command/Control + T`.

![Tabs](https://assets.postman.com/postman-docs/open-unsaved-tab-options-v8.jpg)

> If you open a request and do not edit or send it, then open another, the first tab will be replaced by the second. While the tab is in _Preview_ mode it will display in italics.

You can have multiple tabs open at the same time as you work, and can drag tabs to rearrange them. Use the __...__ button to manage tabs and access recent tabs.

> Duplicating a tab does not mean creating a second request to the same endpoint—when you duplicate a tab any edits you make will affect the original request.

Postman will display a dot on any tabs with unsaved changes.

A tab may indicate a conflict if you or a collaborator changes it in another tab or workspace. Postman will prompt you to resolve any conflicts that occur.

> You can toggle whether Postman opens requests in new tabs or not in the __Settings__, as well as configuring whether Postman prompts you when closing tabs with unsaved changes.

## Next steps

The best way to get to know Postman is by firing up the __Bootcamp__ on the bottom-right and working through the lessons.

![Bootcamp](https://assets.postman.com/postman-docs/bootcamp-lesson-v8.gif)

You can also access Bootcamp together with other resources for getting started and staying up to date by opening **Home** in the upper-left corner.

![Bootcamp Home](https://assets.postman.com/postman-docs/bootcamp-home-v8.jpg)

__Next try [sending your first request](/docs/getting-started/sending-the-first-request/)!__
