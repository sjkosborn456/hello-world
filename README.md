## Welcome to GitHub Pages

<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>STAT 6543 HW2 Osborn</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>




<style type="text/css">
    pre { line-height: 125%; }
td.linenos pre { color: #000000; background-color: #f0f0f0; padding-left: 5px; padding-right: 5px; }
span.linenos { color: #000000; background-color: #f0f0f0; padding-left: 5px; padding-right: 5px; }
td.linenos pre.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>



<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/*
 * Webkit scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-corner {
  background: var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-thumb {
  background: rgb(var(--jp-scrollbar-thumb-color));
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-right: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-bottom: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar */

[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-corner,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-corner {
  background-color: transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-thumb,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid transparent;
  border-right: var(--jp-scrollbar-endpad) solid transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid transparent;
  border-bottom: var(--jp-scrollbar-endpad) solid transparent;
}

/*
 * Phosphor
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Widget, /* </DEPRECATED> */
.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  cursor: default;
}


/* <DEPRECATED> */ .p-Widget.p-mod-hidden, /* </DEPRECATED> */
.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-CommandPalette, /* </DEPRECATED> */
.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-CommandPalette-search, /* </DEPRECATED> */
.lm-CommandPalette-search {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-content, /* </DEPRECATED> */
.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-CommandPalette-header, /* </DEPRECATED> */
.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}


/* <DEPRECATED> */ .p-CommandPalette-item, /* </DEPRECATED> */
.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}


/* <DEPRECATED> */ .p-CommandPalette-itemIcon, /* </DEPRECATED> */
.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemContent, /* </DEPRECATED> */
.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}


/* <DEPRECATED> */ .p-CommandPalette-itemShortcut, /* </DEPRECATED> */
.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemLabel, /* </DEPRECATED> */
.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-DockPanel, /* </DEPRECATED> */
.lm-DockPanel {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-widget, /* </DEPRECATED> */
.lm-DockPanel-widget {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-tabBar, /* </DEPRECATED> */
.lm-DockPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-DockPanel-handle, /* </DEPRECATED> */
.lm-DockPanel-handle {
  z-index: 2;
}


/* <DEPRECATED> */ .p-DockPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-DockPanel-handle:after, /* </DEPRECATED> */
.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}


/* <DEPRECATED> */ .p-DockPanel-overlay, /* </DEPRECATED> */
.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}


/* <DEPRECATED> */ .p-DockPanel-overlay.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Menu, /* </DEPRECATED> */
.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-Menu-content, /* </DEPRECATED> */
.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-Menu-item, /* </DEPRECATED> */
.lm-Menu-item {
  display: table-row;
}


/* <DEPRECATED> */
.p-Menu-item.p-mod-hidden,
.p-Menu-item.p-mod-collapsed,
/* </DEPRECATED> */
.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}


/* <DEPRECATED> */
.p-Menu-itemIcon,
.p-Menu-itemSubmenuIcon,
/* </DEPRECATED> */
.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}


/* <DEPRECATED> */ .p-Menu-itemLabel, /* </DEPRECATED> */
.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}


/* <DEPRECATED> */ .p-Menu-itemShortcut, /* </DEPRECATED> */
.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-MenuBar, /* </DEPRECATED> */
.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-MenuBar-content, /* </DEPRECATED> */
.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}


/* <DEPRECATED> */ .p--MenuBar-item, /* </DEPRECATED> */
.lm-MenuBar-item {
  box-sizing: border-box;
}


/* <DEPRECATED> */
.p-MenuBar-itemIcon,
.p-MenuBar-itemLabel,
/* </DEPRECATED> */
.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-ScrollBar, /* </DEPRECATED> */
.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-ScrollBar-button, /* </DEPRECATED> */
.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-track, /* </DEPRECATED> */
.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-thumb, /* </DEPRECATED> */
.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-SplitPanel-child, /* </DEPRECATED> */
.lm-SplitPanel-child {
  z-index: 0;
}


/* <DEPRECATED> */ .p-SplitPanel-handle, /* </DEPRECATED> */
.lm-SplitPanel-handle {
  z-index: 1;
}


/* <DEPRECATED> */ .p-SplitPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-SplitPanel-handle:after, /* </DEPRECATED> */
.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabBar, /* </DEPRECATED> */
.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='horizontal'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='vertical'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-TabBar-content, /* </DEPRECATED> */
.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='horizontal'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='vertical'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
}


/* <DEPRECATED> */
.p-TabBar-tabIcon,
.p-TabBar-tabCloseIcon,
/* </DEPRECATED> */
.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-TabBar-tabLabel, /* </DEPRECATED> */
.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}


/* <DEPRECATED> */ .p-TabBar-tab.p-mod-hidden, /* </DEPRECATED> */
.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-TabBar.p-mod-dragging .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='horizontal'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='vertical'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging .p-TabBar-tab.p-mod-dragging
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabPanel-tabBar, /* </DEPRECATED> */
.lm-TabPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-TabPanel-stackedPanel, /* </DEPRECATED> */
.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

@charset "UTF-8";
/*!

Copyright 2015-present Palantir Technologies, Inc. All rights reserved.
Licensed under the Apache License, Version 2.0.

*/
html{
  -webkit-box-sizing:border-box;
          box-sizing:border-box; }

*,
*::before,
*::after{
  -webkit-box-sizing:inherit;
          box-sizing:inherit; }

body{
  text-transform:none;
  line-height:1.28581;
  letter-spacing:0;
  font-size:14px;
  font-weight:400;
  color:#182026;
  font-family:-apple-system, "BlinkMacSystemFont", "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Open Sans", "Helvetica Neue", "Icons16", sans-serif; }

p{
  margin-top:0;
  margin-bottom:10px; }

small{
  font-size:12px; }

strong{
  font-weight:600; }

::-moz-selection{
  background:rgba(125, 188, 255, 0.6); }

::selection{
  background:rgba(125, 188, 255, 0.6); }
.bp3-heading{
  color:#182026;
  font-weight:600;
  margin:0 0 10px;
  padding:0; }
  .bp3-dark .bp3-heading{
    color:#f5f8fa; }

h1.bp3-heading, .bp3-running-text h1{
  line-height:40px;
  font-size:36px; }

h2.bp3-heading, .bp3-running-text h2{
  line-height:32px;
  font-size:28px; }

h3.bp3-heading, .bp3-running-text h3{
  line-height:25px;
  font-size:22px; }

h4.bp3-heading, .bp3-running-text h4{
  line-height:21px;
  font-size:18px; }

h5.bp3-heading, .bp3-running-text h5{
  line-height:19px;
  font-size:16px; }

h6.bp3-heading, .bp3-running-text h6{
  line-height:16px;
  font-size:14px; }
.bp3-ui-text{
  text-transform:none;
  line-height:1.28581;
  letter-spacing:0;
  font-size:14px;
  font-weight:400; }

.bp3-monospace-text{
  text-transform:none;
  font-family:monospace; }

.bp3-text-muted{
  color:#5c7080; }
  .bp3-dark .bp3-text-muted{
    color:#a7b6c2; }

.bp3-text-disabled{
  color:rgba(92, 112, 128, 0.6); }
  .bp3-dark .bp3-text-disabled{
    color:rgba(167, 182, 194, 0.6); }

.bp3-text-overflow-ellipsis{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal; }
.bp3-running-text{
  line-height:1.5;
  font-size:14px; }
  .bp3-running-text h1{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h1{
      color:#f5f8fa; }
  .bp3-running-text h2{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h2{
      color:#f5f8fa; }
  .bp3-running-text h3{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h3{
      color:#f5f8fa; }
  .bp3-running-text h4{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h4{
      color:#f5f8fa; }
  .bp3-running-text h5{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h5{
      color:#f5f8fa; }
  .bp3-running-text h6{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h6{
      color:#f5f8fa; }
  .bp3-running-text hr{
    margin:20px 0;
    border:none;
    border-bottom:1px solid rgba(16, 22, 26, 0.15); }
    .bp3-dark .bp3-running-text hr{
      border-color:rgba(255, 255, 255, 0.15); }
  .bp3-running-text p{
    margin:0 0 10px;
    padding:0; }

.bp3-text-large{
  font-size:16px; }

.bp3-text-small{
  font-size:12px; }
a{
  text-decoration:none;
  color:#106ba3; }
  a:hover{
    cursor:pointer;
    text-decoration:underline;
    color:#106ba3; }
  a .bp3-icon, a .bp3-icon-standard, a .bp3-icon-large{
    color:inherit; }
  a code,
  .bp3-dark a code{
    color:inherit; }
  .bp3-dark a,
  .bp3-dark a:hover{
    color:#48aff0; }
    .bp3-dark a .bp3-icon, .bp3-dark a .bp3-icon-standard, .bp3-dark a .bp3-icon-large,
    .bp3-dark a:hover .bp3-icon,
    .bp3-dark a:hover .bp3-icon-standard,
    .bp3-dark a:hover .bp3-icon-large{
      color:inherit; }
.bp3-running-text code, .bp3-code{
  text-transform:none;
  font-family:monospace;
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
  background:rgba(255, 255, 255, 0.7);
  padding:2px 5px;
  color:#5c7080;
  font-size:smaller; }
  .bp3-dark .bp3-running-text code, .bp3-running-text .bp3-dark code, .bp3-dark .bp3-code{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#a7b6c2; }
  .bp3-running-text a > code, a > .bp3-code{
    color:#137cbd; }
    .bp3-dark .bp3-running-text a > code, .bp3-running-text .bp3-dark a > code, .bp3-dark a > .bp3-code{
      color:inherit; }

.bp3-running-text pre, .bp3-code-block{
  text-transform:none;
  font-family:monospace;
  display:block;
  margin:10px 0;
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
  background:rgba(255, 255, 255, 0.7);
  padding:13px 15px 12px;
  line-height:1.4;
  color:#182026;
  font-size:13px;
  word-break:break-all;
  word-wrap:break-word; }
  .bp3-dark .bp3-running-text pre, .bp3-running-text .bp3-dark pre, .bp3-dark .bp3-code-block{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#f5f8fa; }
  .bp3-running-text pre > code, .bp3-code-block > code{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none;
    padding:0;
    color:inherit;
    font-size:inherit; }

.bp3-running-text kbd, .bp3-key{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  min-width:24px;
  height:24px;
  padding:3px 6px;
  vertical-align:middle;
  line-height:24px;
  color:#5c7080;
  font-family:inherit;
  font-size:12px; }
  .bp3-running-text kbd .bp3-icon, .bp3-key .bp3-icon, .bp3-running-text kbd .bp3-icon-standard, .bp3-key .bp3-icon-standard, .bp3-running-text kbd .bp3-icon-large, .bp3-key .bp3-icon-large{
    margin-right:5px; }
  .bp3-dark .bp3-running-text kbd, .bp3-running-text .bp3-dark kbd, .bp3-dark .bp3-key{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
    background:#394b59;
    color:#a7b6c2; }
.bp3-running-text blockquote, .bp3-blockquote{
  margin:0 0 10px;
  border-left:solid 4px rgba(167, 182, 194, 0.5);
  padding:0 20px; }
  .bp3-dark .bp3-running-text blockquote, .bp3-running-text .bp3-dark blockquote, .bp3-dark .bp3-blockquote{
    border-color:rgba(115, 134, 148, 0.5); }
.bp3-running-text ul,
.bp3-running-text ol, .bp3-list{
  margin:10px 0;
  padding-left:30px; }
  .bp3-running-text ul li:not(:last-child), .bp3-running-text ol li:not(:last-child), .bp3-list li:not(:last-child){
    margin-bottom:5px; }
  .bp3-running-text ul ol, .bp3-running-text ol ol, .bp3-list ol,
  .bp3-running-text ul ul,
  .bp3-running-text ol ul,
  .bp3-list ul{
    margin-top:5px; }

.bp3-list-unstyled{
  margin:0;
  padding:0;
  list-style:none; }
  .bp3-list-unstyled li{
    padding:0; }
.bp3-rtl{
  text-align:right; }

.bp3-dark{
  color:#f5f8fa; }

:focus{
  outline:rgba(19, 124, 189, 0.6) auto 2px;
  outline-offset:2px;
  -moz-outline-radius:6px; }

.bp3-focus-disabled :focus{
  outline:none !important; }
  .bp3-focus-disabled :focus ~ .bp3-control-indicator{
    outline:none !important; }

.bp3-alert{
  max-width:400px;
  padding:20px; }

.bp3-alert-body{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-alert-body .bp3-icon{
    margin-top:0;
    margin-right:20px;
    font-size:40px; }

.bp3-alert-footer{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:reverse;
      -ms-flex-direction:row-reverse;
          flex-direction:row-reverse;
  margin-top:10px; }
  .bp3-alert-footer .bp3-button{
    margin-left:10px; }
.bp3-breadcrumbs{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:wrap;
      flex-wrap:wrap;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  margin:0;
  cursor:default;
  height:30px;
  padding:0;
  list-style:none; }
  .bp3-breadcrumbs > li{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center; }
    .bp3-breadcrumbs > li::after{
      display:block;
      margin:0 5px;
      background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M10.71 7.29l-4-4a1.003 1.003 0 0 0-1.42 1.42L8.59 8 5.3 11.29c-.19.18-.3.43-.3.71a1.003 1.003 0 0 0 1.71.71l4-4c.18-.18.29-.43.29-.71 0-.28-.11-.53-.29-.71z' fill='%235C7080'/%3e%3c/svg%3e");
      width:16px;
      height:16px;
      content:""; }
    .bp3-breadcrumbs > li:last-of-type::after{
      display:none; }

.bp3-breadcrumb,
.bp3-breadcrumb-current,
.bp3-breadcrumbs-collapsed{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  font-size:16px; }

.bp3-breadcrumb,
.bp3-breadcrumbs-collapsed{
  color:#5c7080; }

.bp3-breadcrumb:hover{
  text-decoration:none; }

.bp3-breadcrumb.bp3-disabled{
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-breadcrumb .bp3-icon{
  margin-right:5px; }

.bp3-breadcrumb-current{
  color:inherit;
  font-weight:600; }
  .bp3-breadcrumb-current .bp3-input{
    vertical-align:baseline;
    font-size:inherit;
    font-weight:inherit; }

.bp3-breadcrumbs-collapsed{
  margin-right:2px;
  border:none;
  border-radius:3px;
  background:#ced9e0;
  cursor:pointer;
  padding:1px 5px;
  vertical-align:text-bottom; }
  .bp3-breadcrumbs-collapsed::before{
    display:block;
    background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cg fill='%235C7080'%3e%3ccircle cx='2' cy='8.03' r='2'/%3e%3ccircle cx='14' cy='8.03' r='2'/%3e%3ccircle cx='8' cy='8.03' r='2'/%3e%3c/g%3e%3c/svg%3e") center no-repeat;
    width:16px;
    height:16px;
    content:""; }
  .bp3-breadcrumbs-collapsed:hover{
    background:#bfccd6;
    text-decoration:none;
    color:#182026; }

.bp3-dark .bp3-breadcrumb,
.bp3-dark .bp3-breadcrumbs-collapsed{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumbs > li::after{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumb.bp3-disabled{
  color:rgba(167, 182, 194, 0.6); }

.bp3-dark .bp3-breadcrumb-current{
  color:#f5f8fa; }

.bp3-dark .bp3-breadcrumbs-collapsed{
  background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-breadcrumbs-collapsed:hover{
    background:rgba(16, 22, 26, 0.6);
    color:#f5f8fa; }
.bp3-button{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  padding:5px 10px;
  vertical-align:middle;
  text-align:left;
  font-size:14px;
  min-width:30px;
  min-height:30px; }
  .bp3-button > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-button > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-button::before,
  .bp3-button > *{
    margin-right:7px; }
  .bp3-button:empty::before,
  .bp3-button > :last-child{
    margin-right:0; }
  .bp3-button:empty{
    padding:0 !important; }
  .bp3-button:disabled, .bp3-button.bp3-disabled{
    cursor:not-allowed; }
  .bp3-button.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button.bp3-align-right,
  .bp3-align-right .bp3-button{
    text-align:right; }
  .bp3-button.bp3-align-left,
  .bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-button:not([class*="bp3-intent-"]){
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    color:#182026; }
    .bp3-button:not([class*="bp3-intent-"]):hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
      background-clip:padding-box;
      background-color:#ebf1f5; }
    .bp3-button:not([class*="bp3-intent-"]):active, .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#d8e1e8;
      background-image:none; }
    .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      outline:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active:hover, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-button.bp3-intent-primary{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover, .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#106ba3; }
    .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#0e5a8a;
      background-image:none; }
    .bp3-button.bp3-intent-primary:disabled, .bp3-button.bp3-intent-primary.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(19, 124, 189, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-success{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#0f9960;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-success:hover, .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-success:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#0d8050; }
    .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#0a6640;
      background-image:none; }
    .bp3-button.bp3-intent-success:disabled, .bp3-button.bp3-intent-success.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(15, 153, 96, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-warning{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#d9822b;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover, .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#bf7326; }
    .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#a66321;
      background-image:none; }
    .bp3-button.bp3-intent-warning:disabled, .bp3-button.bp3-intent-warning.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(217, 130, 43, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-danger{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#db3737;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover, .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#c23030; }
    .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#a82a2a;
      background-image:none; }
    .bp3-button.bp3-intent-danger:disabled, .bp3-button.bp3-intent-danger.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(219, 55, 55, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
    stroke:#ffffff; }
  .bp3-button.bp3-large,
  .bp3-large .bp3-button{
    min-width:40px;
    min-height:40px;
    padding:5px 15px;
    font-size:16px; }
    .bp3-button.bp3-large::before,
    .bp3-button.bp3-large > *,
    .bp3-large .bp3-button::before,
    .bp3-large .bp3-button > *{
      margin-right:10px; }
    .bp3-button.bp3-large:empty::before,
    .bp3-button.bp3-large > :last-child,
    .bp3-large .bp3-button:empty::before,
    .bp3-large .bp3-button > :last-child{
      margin-right:0; }
  .bp3-button.bp3-small,
  .bp3-small .bp3-button{
    min-width:24px;
    min-height:24px;
    padding:0 7px; }
  .bp3-button.bp3-loading{
    position:relative; }
    .bp3-button.bp3-loading[class*="bp3-icon-"]::before{
      visibility:hidden; }
    .bp3-button.bp3-loading .bp3-button-spinner{
      position:absolute;
      margin:0; }
    .bp3-button.bp3-loading > :not(.bp3-button-spinner){
      visibility:hidden; }
  .bp3-button[class*="bp3-icon-"]::before{
    line-height:1;
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-weight:400;
    font-style:normal;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    color:#5c7080; }
  .bp3-button .bp3-icon, .bp3-button .bp3-icon-standard, .bp3-button .bp3-icon-large{
    color:#5c7080; }
    .bp3-button .bp3-icon.bp3-align-right, .bp3-button .bp3-icon-standard.bp3-align-right, .bp3-button .bp3-icon-large.bp3-align-right{
      margin-left:7px; }
  .bp3-button .bp3-icon:first-child:last-child,
  .bp3-button .bp3-spinner + .bp3-icon:last-child{
    margin:0 -7px; }
  .bp3-dark .bp3-button:not([class*="bp3-intent-"]){
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover, .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#30404d; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#202b33;
      background-image:none; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"])[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-large{
      color:#a7b6c2; }
  .bp3-dark .bp3-button[class*="bp3-intent-"]{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:active, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:disabled, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background-image:none;
      color:rgba(255, 255, 255, 0.3); }
    .bp3-dark .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
      stroke:#8a9ba8; }
  .bp3-button:disabled::before,
  .bp3-button:disabled .bp3-icon, .bp3-button:disabled .bp3-icon-standard, .bp3-button:disabled .bp3-icon-large, .bp3-button.bp3-disabled::before,
  .bp3-button.bp3-disabled .bp3-icon, .bp3-button.bp3-disabled .bp3-icon-standard, .bp3-button.bp3-disabled .bp3-icon-large, .bp3-button[class*="bp3-intent-"]::before,
  .bp3-button[class*="bp3-intent-"] .bp3-icon, .bp3-button[class*="bp3-intent-"] .bp3-icon-standard, .bp3-button[class*="bp3-intent-"] .bp3-icon-large{
    color:inherit !important; }
  .bp3-button.bp3-minimal{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none; }
    .bp3-button.bp3-minimal:hover{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(167, 182, 194, 0.3);
      text-decoration:none;
      color:#182026; }
    .bp3-button.bp3-minimal:active, .bp3-button.bp3-minimal.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(115, 134, 148, 0.3);
      color:#182026; }
    .bp3-button.bp3-minimal:disabled, .bp3-button.bp3-minimal:disabled:hover, .bp3-button.bp3-minimal.bp3-disabled, .bp3-button.bp3-minimal.bp3-disabled:hover{
      background:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-minimal{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-minimal:hover, .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none; }
      .bp3-dark .bp3-button.bp3-minimal:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-minimal:disabled, .bp3-dark .bp3-button.bp3-minimal:disabled:hover, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover{
        background:none;
        cursor:not-allowed;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover, .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-success{
      color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover, .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover, .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-danger{
      color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover, .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }

a.bp3-button{
  text-align:center;
  text-decoration:none;
  -webkit-transition:none;
  transition:none; }
  a.bp3-button, a.bp3-button:hover, a.bp3-button:active{
    color:#182026; }
  a.bp3-button.bp3-disabled{
    color:rgba(92, 112, 128, 0.6); }

.bp3-button-text{
  -webkit-box-flex:0;
      -ms-flex:0 1 auto;
          flex:0 1 auto; }

.bp3-button.bp3-align-left .bp3-button-text, .bp3-button.bp3-align-right .bp3-button-text,
.bp3-button-group.bp3-align-left .bp3-button-text,
.bp3-button-group.bp3-align-right .bp3-button-text{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto; }
.bp3-button-group{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex; }
  .bp3-button-group .bp3-button{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    position:relative;
    z-index:4; }
    .bp3-button-group .bp3-button:focus{
      z-index:5; }
    .bp3-button-group .bp3-button:hover{
      z-index:6; }
    .bp3-button-group .bp3-button:active, .bp3-button-group .bp3-button.bp3-active{
      z-index:7; }
    .bp3-button-group .bp3-button:disabled, .bp3-button-group .bp3-button.bp3-disabled{
      z-index:3; }
    .bp3-button-group .bp3-button[class*="bp3-intent-"]{
      z-index:9; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:focus{
        z-index:10; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:hover{
        z-index:11; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:active, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-active{
        z-index:12; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:disabled, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-disabled{
        z-index:8; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:first-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:first-child){
    border-top-left-radius:0;
    border-bottom-left-radius:0; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    margin-right:-1px;
    border-top-right-radius:0;
    border-bottom-right-radius:0; }
  .bp3-button-group.bp3-minimal .bp3-button{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none; }
    .bp3-button-group.bp3-minimal .bp3-button:hover{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(167, 182, 194, 0.3);
      text-decoration:none;
      color:#182026; }
    .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(115, 134, 148, 0.3);
      color:#182026; }
    .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
      background:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button-group.bp3-minimal .bp3-button{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:inherit; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
        background:none;
        cursor:not-allowed;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
      color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
      color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
  .bp3-button-group .bp3-popover-wrapper,
  .bp3-button-group .bp3-popover-target{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button-group .bp3-button.bp3-fill,
  .bp3-button-group.bp3-fill .bp3-button:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-vertical{
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column;
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    vertical-align:top; }
    .bp3-button-group.bp3-vertical.bp3-fill{
      width:unset;
      height:100%; }
    .bp3-button-group.bp3-vertical .bp3-button{
      margin-right:0 !important;
      width:100%; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:first-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:first-child{
      border-radius:3px 3px 0 0; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:last-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:last-child{
      border-radius:0 0 3px 3px; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:not(:last-child){
      margin-bottom:-1px; }
  .bp3-button-group.bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    margin-right:1px; }
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-button:not(:last-child){
    margin-bottom:1px; }
.bp3-callout{
  line-height:1.5;
  font-size:14px;
  position:relative;
  border-radius:3px;
  background-color:rgba(138, 155, 168, 0.15);
  width:100%;
  padding:10px 12px 9px; }
  .bp3-callout[class*="bp3-icon-"]{
    padding-left:40px; }
    .bp3-callout[class*="bp3-icon-"]::before{
      line-height:1;
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-weight:400;
      font-style:normal;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      position:absolute;
      top:10px;
      left:10px;
      color:#5c7080; }
  .bp3-callout.bp3-callout-icon{
    padding-left:40px; }
    .bp3-callout.bp3-callout-icon > .bp3-icon:first-child{
      position:absolute;
      top:10px;
      left:10px;
      color:#5c7080; }
  .bp3-callout .bp3-heading{
    margin-top:0;
    margin-bottom:5px;
    line-height:20px; }
    .bp3-callout .bp3-heading:last-child{
      margin-bottom:0; }
  .bp3-dark .bp3-callout{
    background-color:rgba(138, 155, 168, 0.2); }
    .bp3-dark .bp3-callout[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
  .bp3-callout.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15); }
    .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-primary .bp3-heading{
      color:#106ba3; }
    .bp3-dark .bp3-callout.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-primary .bp3-heading{
        color:#48aff0; }
  .bp3-callout.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15); }
    .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-success .bp3-heading{
      color:#0d8050; }
    .bp3-dark .bp3-callout.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-success .bp3-heading{
        color:#3dcc91; }
  .bp3-callout.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15); }
    .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-warning .bp3-heading{
      color:#bf7326; }
    .bp3-dark .bp3-callout.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-warning .bp3-heading{
        color:#ffb366; }
  .bp3-callout.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15); }
    .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-danger .bp3-heading{
      color:#c23030; }
    .bp3-dark .bp3-callout.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-danger .bp3-heading{
        color:#ff7373; }
  .bp3-running-text .bp3-callout{
    margin:20px 0; }
.bp3-card{
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
  background-color:#ffffff;
  padding:20px;
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-card.bp3-dark,
  .bp3-dark .bp3-card{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
    background-color:#30404d; }

.bp3-elevation-0{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }
  .bp3-elevation-0.bp3-dark,
  .bp3-dark .bp3-elevation-0{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }

.bp3-elevation-1{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-1.bp3-dark,
  .bp3-dark .bp3-elevation-1{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-elevation-2{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-2.bp3-dark,
  .bp3-dark .bp3-elevation-2{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4); }

.bp3-elevation-3{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-3.bp3-dark,
  .bp3-dark .bp3-elevation-3{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-elevation-4{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-4.bp3-dark,
  .bp3-dark .bp3-elevation-4{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:hover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  cursor:pointer; }
  .bp3-card.bp3-interactive:hover.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:hover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:active{
  opacity:0.9;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  -webkit-transition-duration:0;
          transition-duration:0; }
  .bp3-card.bp3-interactive:active.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:active{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-collapse{
  height:0;
  overflow-y:hidden;
  -webkit-transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-collapse .bp3-collapse-body{
    -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-collapse .bp3-collapse-body[aria-hidden="true"]{
      display:none; }

.bp3-context-menu .bp3-popover-target{
  display:block; }

.bp3-context-menu-popover-target{
  position:fixed; }

.bp3-divider{
  margin:5px;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  border-bottom:1px solid rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-dialog-container{
  opacity:1;
  -webkit-transform:scale(1);
          transform:scale(1);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  width:100%;
  min-height:100%;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-dialog-container.bp3-overlay-enter > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5); }
  .bp3-dialog-container.bp3-overlay-enter-active > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear-active > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-dialog-container.bp3-overlay-exit > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-dialog-container.bp3-overlay-exit-active > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5);
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }

.bp3-dialog{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:30px 0;
  border-radius:6px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  background:#ebf1f5;
  width:500px;
  padding-bottom:20px;
  pointer-events:all;
  -webkit-user-select:text;
     -moz-user-select:text;
      -ms-user-select:text;
          user-select:text; }
  .bp3-dialog:focus{
    outline:0; }
  .bp3-dialog.bp3-dark,
  .bp3-dark .bp3-dialog{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    background:#293742;
    color:#f5f8fa; }

.bp3-dialog-header{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border-radius:6px 6px 0 0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  background:#ffffff;
  min-height:40px;
  padding-right:5px;
  padding-left:20px; }
  .bp3-dialog-header .bp3-icon-large,
  .bp3-dialog-header .bp3-icon{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px;
    color:#5c7080; }
  .bp3-dialog-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    margin:0;
    line-height:inherit; }
    .bp3-dialog-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-dialog-header{
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
    background:#30404d; }
    .bp3-dark .bp3-dialog-header .bp3-icon-large,
    .bp3-dark .bp3-dialog-header .bp3-icon{
      color:#a7b6c2; }

.bp3-dialog-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  margin:20px;
  line-height:18px; }

.bp3-dialog-footer{
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  margin:0 20px; }

.bp3-dialog-footer-actions{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:end;
      -ms-flex-pack:end;
          justify-content:flex-end; }
  .bp3-dialog-footer-actions .bp3-button{
    margin-left:10px; }
.bp3-drawer{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  padding:0; }
  .bp3-drawer:focus{
    outline:0; }
  .bp3-drawer.bp3-position-top{
    top:0;
    right:0;
    left:0;
    height:50%; }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter, .bp3-drawer.bp3-position-top.bp3-overlay-appear{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%); }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter-active, .bp3-drawer.bp3-position-top.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit-active{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-position-bottom{
    right:0;
    bottom:0;
    left:0;
    height:50%; }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter-active, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-position-left{
    top:0;
    bottom:0;
    left:0;
    width:50%; }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter, .bp3-drawer.bp3-position-left.bp3-overlay-appear{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%); }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter-active, .bp3-drawer.bp3-position-left.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit-active{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-position-right{
    top:0;
    right:0;
    bottom:0;
    width:50%; }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter, .bp3-drawer.bp3-position-right.bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter-active, .bp3-drawer.bp3-position-right.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right):not(.bp3-vertical){
    top:0;
    right:0;
    bottom:0;
    width:50%; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right).bp3-vertical{
    right:0;
    bottom:0;
    left:0;
    height:50%; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-dark,
  .bp3-dark .bp3-drawer{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    background:#30404d;
    color:#f5f8fa; }

.bp3-drawer-header{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  position:relative;
  border-radius:0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  min-height:40px;
  padding:5px;
  padding-left:20px; }
  .bp3-drawer-header .bp3-icon-large,
  .bp3-drawer-header .bp3-icon{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px;
    color:#5c7080; }
  .bp3-drawer-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    margin:0;
    line-height:inherit; }
    .bp3-drawer-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-drawer-header{
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-drawer-header .bp3-icon-large,
    .bp3-dark .bp3-drawer-header .bp3-icon{
      color:#a7b6c2; }

.bp3-drawer-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  overflow:auto;
  line-height:18px; }

.bp3-drawer-footer{
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  position:relative;
  -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
  padding:10px 20px; }
  .bp3-dark .bp3-drawer-footer{
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4); }
.bp3-editable-text{
  display:inline-block;
  position:relative;
  cursor:text;
  max-width:100%;
  vertical-align:top;
  white-space:nowrap; }
  .bp3-editable-text::before{
    position:absolute;
    top:-3px;
    right:-3px;
    bottom:-3px;
    left:-3px;
    border-radius:3px;
    content:"";
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-editable-text.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
    background-color:#ffffff; }
  .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#137cbd; }
  .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4); }
  .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#0f9960; }
  .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4); }
  .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#d9822b; }
  .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4); }
  .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#db3737; }
  .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4); }
  .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15); }
  .bp3-dark .bp3-editable-text.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background-color:rgba(16, 22, 26, 0.3); }
  .bp3-dark .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#48aff0; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4);
            box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#3dcc91; }
  .bp3-dark .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4);
            box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#ffb366; }
  .bp3-dark .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4);
            box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#ff7373; }
  .bp3-dark .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4);
            box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-editable-text-input,
.bp3-editable-text-content{
  display:inherit;
  position:relative;
  min-width:inherit;
  max-width:inherit;
  vertical-align:top;
  text-transform:inherit;
  letter-spacing:inherit;
  color:inherit;
  font:inherit;
  resize:none; }

.bp3-editable-text-input{
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  background:none;
  width:100%;
  padding:0;
  white-space:pre-wrap; }
  .bp3-editable-text-input::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input:focus{
    outline:none; }
  .bp3-editable-text-input::-ms-clear{
    display:none; }

.bp3-editable-text-content{
  overflow:hidden;
  padding-right:2px;
  text-overflow:ellipsis;
  white-space:pre; }
  .bp3-editable-text-editing > .bp3-editable-text-content{
    position:absolute;
    left:0;
    visibility:hidden; }
  .bp3-editable-text-placeholder > .bp3-editable-text-content{
    color:rgba(92, 112, 128, 0.6); }
    .bp3-dark .bp3-editable-text-placeholder > .bp3-editable-text-content{
      color:rgba(167, 182, 194, 0.6); }

.bp3-editable-text.bp3-multiline{
  display:block; }
  .bp3-editable-text.bp3-multiline .bp3-editable-text-content{
    overflow:auto;
    white-space:pre-wrap;
    word-wrap:break-word; }
.bp3-control-group{
  -webkit-transform:translateZ(0);
          transform:translateZ(0);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:stretch;
      -ms-flex-align:stretch;
          align-items:stretch; }
  .bp3-control-group > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select,
  .bp3-control-group .bp3-input,
  .bp3-control-group .bp3-select{
    position:relative; }
  .bp3-control-group .bp3-input{
    z-index:2;
    border-radius:inherit; }
    .bp3-control-group .bp3-input:focus{
      z-index:14;
      border-radius:3px; }
    .bp3-control-group .bp3-input[class*="bp3-intent"]{
      z-index:13; }
      .bp3-control-group .bp3-input[class*="bp3-intent"]:focus{
        z-index:15; }
    .bp3-control-group .bp3-input[readonly], .bp3-control-group .bp3-input:disabled, .bp3-control-group .bp3-input.bp3-disabled{
      z-index:1; }
  .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input{
    z-index:13; }
    .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input:focus{
      z-index:15; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select select,
  .bp3-control-group .bp3-select select{
    -webkit-transform:translateZ(0);
            transform:translateZ(0);
    z-index:4;
    border-radius:inherit; }
    .bp3-control-group .bp3-button:focus,
    .bp3-control-group .bp3-html-select select:focus,
    .bp3-control-group .bp3-select select:focus{
      z-index:5; }
    .bp3-control-group .bp3-button:hover,
    .bp3-control-group .bp3-html-select select:hover,
    .bp3-control-group .bp3-select select:hover{
      z-index:6; }
    .bp3-control-group .bp3-button:active,
    .bp3-control-group .bp3-html-select select:active,
    .bp3-control-group .bp3-select select:active{
      z-index:7; }
    .bp3-control-group .bp3-button[readonly], .bp3-control-group .bp3-button:disabled, .bp3-control-group .bp3-button.bp3-disabled,
    .bp3-control-group .bp3-html-select select[readonly],
    .bp3-control-group .bp3-html-select select:disabled,
    .bp3-control-group .bp3-html-select select.bp3-disabled,
    .bp3-control-group .bp3-select select[readonly],
    .bp3-control-group .bp3-select select:disabled,
    .bp3-control-group .bp3-select select.bp3-disabled{
      z-index:3; }
    .bp3-control-group .bp3-button[class*="bp3-intent"],
    .bp3-control-group .bp3-html-select select[class*="bp3-intent"],
    .bp3-control-group .bp3-select select[class*="bp3-intent"]{
      z-index:9; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:focus{
        z-index:10; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:hover{
        z-index:11; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:active{
        z-index:12; }
      .bp3-control-group .bp3-button[class*="bp3-intent"][readonly], .bp3-control-group .bp3-button[class*="bp3-intent"]:disabled, .bp3-control-group .bp3-button[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"].bp3-disabled{
        z-index:8; }
  .bp3-control-group .bp3-input-group > .bp3-icon,
  .bp3-control-group .bp3-input-group > .bp3-button,
  .bp3-control-group .bp3-input-group > .bp3-input-action{
    z-index:16; }
  .bp3-control-group .bp3-select::after,
  .bp3-control-group .bp3-html-select::after,
  .bp3-control-group .bp3-select > .bp3-icon,
  .bp3-control-group .bp3-html-select > .bp3-icon{
    z-index:17; }
  .bp3-control-group:not(.bp3-vertical) > *{
    margin-right:-1px; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > *{
    margin-right:0; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > .bp3-button + .bp3-button{
    margin-left:1px; }
  .bp3-control-group .bp3-popover-wrapper,
  .bp3-control-group .bp3-popover-target{
    border-radius:inherit; }
  .bp3-control-group > :first-child{
    border-radius:3px 0 0 3px; }
  .bp3-control-group > :last-child{
    margin-right:0;
    border-radius:0 3px 3px 0; }
  .bp3-control-group > :only-child{
    margin-right:0;
    border-radius:3px; }
  .bp3-control-group .bp3-input-group .bp3-button{
    border-radius:3px; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-fill > *:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-vertical{
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column; }
    .bp3-control-group.bp3-vertical > *{
      margin-top:-1px; }
    .bp3-control-group.bp3-vertical > :first-child{
      margin-top:0;
      border-radius:3px 3px 0 0; }
    .bp3-control-group.bp3-vertical > :last-child{
      border-radius:0 0 3px 3px; }
.bp3-control{
  display:block;
  position:relative;
  margin-bottom:10px;
  cursor:pointer;
  text-transform:none; }
  .bp3-control input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
  .bp3-control:hover input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#106ba3; }
  .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background:#0e5a8a; }
  .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(19, 124, 189, 0.5); }
  .bp3-dark .bp3-control input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control:hover input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#106ba3; }
  .bp3-dark .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#0e5a8a; }
  .bp3-dark .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(14, 90, 138, 0.5); }
  .bp3-control:not(.bp3-align-right){
    padding-left:26px; }
    .bp3-control:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-26px; }
  .bp3-control.bp3-align-right{
    padding-right:26px; }
    .bp3-control.bp3-align-right .bp3-control-indicator{
      margin-right:-26px; }
  .bp3-control.bp3-disabled{
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-control.bp3-inline{
    display:inline-block;
    margin-right:20px; }
  .bp3-control input{
    position:absolute;
    top:0;
    left:0;
    opacity:0;
    z-index:-1; }
  .bp3-control .bp3-control-indicator{
    display:inline-block;
    position:relative;
    margin-top:-3px;
    margin-right:10px;
    border:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    cursor:pointer;
    width:1em;
    height:1em;
    vertical-align:middle;
    font-size:16px;
    -webkit-user-select:none;
       -moz-user-select:none;
        -ms-user-select:none;
            user-select:none; }
    .bp3-control .bp3-control-indicator::before{
      display:block;
      width:1em;
      height:1em;
      content:""; }
  .bp3-control:hover .bp3-control-indicator{
    background-color:#ebf1f5; }
  .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background:#d8e1e8; }
  .bp3-control input:disabled ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(206, 217, 224, 0.5);
    cursor:not-allowed; }
  .bp3-control input:focus ~ .bp3-control-indicator{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:2px;
    -moz-outline-radius:6px; }
  .bp3-control.bp3-align-right .bp3-control-indicator{
    float:right;
    margin-top:1px;
    margin-left:10px; }
  .bp3-control.bp3-large{
    font-size:16px; }
    .bp3-control.bp3-large:not(.bp3-align-right){
      padding-left:30px; }
      .bp3-control.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
        margin-left:-30px; }
    .bp3-control.bp3-large.bp3-align-right{
      padding-right:30px; }
      .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
        margin-right:-30px; }
    .bp3-control.bp3-large .bp3-control-indicator{
      font-size:20px; }
    .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-top:0; }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
  .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#106ba3; }
  .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background:#0e5a8a; }
  .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(19, 124, 189, 0.5); }
  .bp3-dark .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#106ba3; }
  .bp3-dark .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#0e5a8a; }
  .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(14, 90, 138, 0.5); }
  .bp3-control.bp3-checkbox .bp3-control-indicator{
    border-radius:3px; }
  .bp3-control.bp3-checkbox input:checked ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M12 5c-.28 0-.53.11-.71.29L7 9.59l-2.29-2.3a1.003 1.003 0 0 0-1.42 1.42l3 3c.18.18.43.29.71.29s.53-.11.71-.29l5-5A1.003 1.003 0 0 0 12 5z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M11 7H5c-.55 0-1 .45-1 1s.45 1 1 1h6c.55 0 1-.45 1-1s-.45-1-1-1z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-radio .bp3-control-indicator{
    border-radius:50%; }
  .bp3-control.bp3-radio input:checked ~ .bp3-control-indicator::before{
    background-image:radial-gradient(#ffffff, #ffffff 28%, transparent 32%); }
  .bp3-control.bp3-radio input:checked:disabled ~ .bp3-control-indicator::before{
    opacity:0.5; }
  .bp3-control.bp3-radio input:focus ~ .bp3-control-indicator{
    -moz-outline-radius:16px; }
  .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(167, 182, 194, 0.5); }
  .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(115, 134, 148, 0.5); }
  .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(92, 112, 128, 0.5); }
  .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(206, 217, 224, 0.5); }
    .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5); }
    .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch:not(.bp3-align-right){
    padding-left:38px; }
    .bp3-control.bp3-switch:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-38px; }
  .bp3-control.bp3-switch.bp3-align-right{
    padding-right:38px; }
    .bp3-control.bp3-switch.bp3-align-right .bp3-control-indicator{
      margin-right:-38px; }
  .bp3-control.bp3-switch .bp3-control-indicator{
    border:none;
    border-radius:1.75em;
    -webkit-box-shadow:none !important;
            box-shadow:none !important;
    width:auto;
    min-width:1.75em;
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-control.bp3-switch .bp3-control-indicator::before{
      position:absolute;
      left:0;
      margin:2px;
      border-radius:50%;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
      background:#ffffff;
      width:calc(1em - 4px);
      height:calc(1em - 4px);
      -webkit-transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    left:calc(100% - 1em); }
  .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right){
    padding-left:45px; }
    .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-45px; }
  .bp3-control.bp3-switch.bp3-large.bp3-align-right{
    padding-right:45px; }
    .bp3-control.bp3-switch.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-right:-45px; }
  .bp3-dark .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.7); }
  .bp3-dark .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.9); }
  .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(57, 75, 89, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-dark .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-dark .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch .bp3-control-indicator::before{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background:#394b59; }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-control.bp3-switch .bp3-switch-inner-text{
    text-align:center;
    font-size:0.7em; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:first-child{
    visibility:hidden;
    margin-right:1.2em;
    margin-left:0.5em;
    line-height:0; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:last-child{
    visibility:visible;
    margin-right:0.5em;
    margin-left:1.2em;
    line-height:1em; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:first-child{
    visibility:visible;
    line-height:1em; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:last-child{
    visibility:hidden;
    line-height:0; }
  .bp3-dark .bp3-control{
    color:#f5f8fa; }
    .bp3-dark .bp3-control.bp3-disabled{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-control .bp3-control-indicator{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0)); }
    .bp3-dark .bp3-control:hover .bp3-control-indicator{
      background-color:#30404d; }
    .bp3-dark .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background:#202b33; }
    .bp3-dark .bp3-control input:disabled ~ .bp3-control-indicator{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      cursor:not-allowed; }
    .bp3-dark .bp3-control.bp3-checkbox input:disabled:checked ~ .bp3-control-indicator, .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
      color:rgba(167, 182, 194, 0.6); }
.bp3-file-input{
  display:inline-block;
  position:relative;
  cursor:pointer;
  height:30px; }
  .bp3-file-input input{
    opacity:0;
    margin:0;
    min-width:200px; }
    .bp3-file-input input:disabled + .bp3-file-upload-input,
    .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(206, 217, 224, 0.5);
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6);
      resize:none; }
      .bp3-file-input input:disabled + .bp3-file-upload-input::after,
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
        outline:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        background-color:rgba(206, 217, 224, 0.5);
        background-image:none;
        cursor:not-allowed;
        color:rgba(92, 112, 128, 0.6); }
        .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active:hover,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active:hover{
          background:rgba(206, 217, 224, 0.7); }
      .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input, .bp3-dark
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:rgba(57, 75, 89, 0.5);
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after, .bp3-dark
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
          -webkit-box-shadow:none;
                  box-shadow:none;
          background-color:rgba(57, 75, 89, 0.5);
          background-image:none;
          color:rgba(167, 182, 194, 0.6); }
          .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-dark
          .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active{
            background:rgba(57, 75, 89, 0.7); }
  .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#182026; }
  .bp3-dark .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#f5f8fa; }
  .bp3-file-input.bp3-fill{
    width:100%; }
  .bp3-file-input.bp3-large,
  .bp3-large .bp3-file-input{
    height:40px; }
  .bp3-file-input .bp3-file-upload-input-custom-text::after{
    content:attr(bp3-button-text); }

.bp3-file-upload-input{
  outline:none;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  height:30px;
  padding:0 10px;
  vertical-align:middle;
  line-height:30px;
  color:#182026;
  font-size:14px;
  font-weight:400;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  position:absolute;
  top:0;
  right:0;
  left:0;
  padding-right:80px;
  color:rgba(92, 112, 128, 0.6);
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-file-upload-input::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input:focus, .bp3-file-upload-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-file-upload-input[type="search"], .bp3-file-upload-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-file-upload-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-file-upload-input:disabled, .bp3-file-upload-input.bp3-disabled{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(206, 217, 224, 0.5);
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6);
    resize:none; }
  .bp3-file-upload-input::after{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    color:#182026;
    min-width:24px;
    min-height:24px;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    position:absolute;
    top:0;
    right:0;
    margin:3px;
    border-radius:3px;
    width:70px;
    text-align:center;
    line-height:24px;
    content:"Browse"; }
    .bp3-file-upload-input::after:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
      background-clip:padding-box;
      background-color:#ebf1f5; }
    .bp3-file-upload-input::after:active, .bp3-file-upload-input::after.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#d8e1e8;
      background-image:none; }
    .bp3-file-upload-input::after:disabled, .bp3-file-upload-input::after.bp3-disabled{
      outline:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-file-upload-input::after:disabled.bp3-active, .bp3-file-upload-input::after:disabled.bp3-active:hover, .bp3-file-upload-input::after.bp3-disabled.bp3-active, .bp3-file-upload-input::after.bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-file-upload-input:hover::after{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5; }
  .bp3-file-upload-input:active::after{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none; }
  .bp3-large .bp3-file-upload-input{
    height:40px;
    line-height:40px;
    font-size:16px;
    padding-right:95px; }
    .bp3-large .bp3-file-upload-input[type="search"], .bp3-large .bp3-file-upload-input.bp3-round{
      padding:0 15px; }
    .bp3-large .bp3-file-upload-input::after{
      min-width:30px;
      min-height:30px;
      margin:5px;
      width:85px;
      line-height:30px; }
  .bp3-dark .bp3-file-upload-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#f5f8fa;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input:disabled, .bp3-dark .bp3-file-upload-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::after{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover, .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover{
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
        background-color:#30404d; }
      .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
        background-color:#202b33;
        background-image:none; }
      .bp3-dark .bp3-file-upload-input::after:disabled, .bp3-dark .bp3-file-upload-input::after.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none;
        background-color:rgba(57, 75, 89, 0.5);
        background-image:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-upload-input::after:disabled.bp3-active, .bp3-dark .bp3-file-upload-input::after.bp3-disabled.bp3-active{
          background:rgba(57, 75, 89, 0.7); }
      .bp3-dark .bp3-file-upload-input::after .bp3-button-spinner .bp3-spinner-head{
        background:rgba(16, 22, 26, 0.5);
        stroke:#8a9ba8; }
    .bp3-dark .bp3-file-upload-input:hover::after{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#30404d; }
    .bp3-dark .bp3-file-upload-input:active::after{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#202b33;
      background-image:none; }

.bp3-file-upload-input::after{
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
.bp3-form-group{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0 0 15px; }
  .bp3-form-group label.bp3-label{
    margin-bottom:5px; }
  .bp3-form-group .bp3-control{
    margin-top:7px; }
  .bp3-form-group .bp3-form-helper-text{
    margin-top:5px;
    color:#5c7080;
    font-size:12px; }
  .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#106ba3; }
  .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#0d8050; }
  .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#bf7326; }
  .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#c23030; }
  .bp3-form-group.bp3-inline{
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row;
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
    .bp3-form-group.bp3-inline.bp3-large label.bp3-label{
      margin:0 10px 0 0;
      line-height:40px; }
    .bp3-form-group.bp3-inline label.bp3-label{
      margin:0 10px 0 0;
      line-height:30px; }
  .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-dark .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#48aff0; }
  .bp3-dark .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#3dcc91; }
  .bp3-dark .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#ffb366; }
  .bp3-dark .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#ff7373; }
  .bp3-dark .bp3-form-group .bp3-form-helper-text{
    color:#a7b6c2; }
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(167, 182, 194, 0.6) !important; }
.bp3-input-group{
  display:block;
  position:relative; }
  .bp3-input-group .bp3-input{
    position:relative;
    width:100%; }
    .bp3-input-group .bp3-input:not(:first-child){
      padding-left:30px; }
    .bp3-input-group .bp3-input:not(:last-child){
      padding-right:30px; }
  .bp3-input-group .bp3-input-action,
  .bp3-input-group > .bp3-button,
  .bp3-input-group > .bp3-icon{
    position:absolute;
    top:0; }
    .bp3-input-group .bp3-input-action:first-child,
    .bp3-input-group > .bp3-button:first-child,
    .bp3-input-group > .bp3-icon:first-child{
      left:0; }
    .bp3-input-group .bp3-input-action:last-child,
    .bp3-input-group > .bp3-button:last-child,
    .bp3-input-group > .bp3-icon:last-child{
      right:0; }
  .bp3-input-group .bp3-button{
    min-width:24px;
    min-height:24px;
    margin:3px;
    padding:0 7px; }
    .bp3-input-group .bp3-button:empty{
      padding:0; }
  .bp3-input-group > .bp3-icon{
    z-index:1;
    color:#5c7080; }
    .bp3-input-group > .bp3-icon:empty{
      line-height:1;
      font-family:"Icons16", sans-serif;
      font-size:16px;
      font-weight:400;
      font-style:normal;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased; }
  .bp3-input-group > .bp3-icon,
  .bp3-input-group .bp3-input-action > .bp3-spinner{
    margin:7px; }
  .bp3-input-group .bp3-tag{
    margin:5px; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus),
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
    color:#5c7080; }
    .bp3-dark .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus), .bp3-dark
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
      color:#a7b6c2; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large{
      color:#5c7080; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled,
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled{
    color:rgba(92, 112, 128, 0.6) !important; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-large{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-input-group.bp3-disabled{
    cursor:not-allowed; }
    .bp3-input-group.bp3-disabled .bp3-icon{
      color:rgba(92, 112, 128, 0.6); }
  .bp3-input-group.bp3-large .bp3-button{
    min-width:30px;
    min-height:30px;
    margin:5px; }
  .bp3-input-group.bp3-large > .bp3-icon,
  .bp3-input-group.bp3-large .bp3-input-action > .bp3-spinner{
    margin:12px; }
  .bp3-input-group.bp3-large .bp3-input{
    height:40px;
    line-height:40px;
    font-size:16px; }
    .bp3-input-group.bp3-large .bp3-input[type="search"], .bp3-input-group.bp3-large .bp3-input.bp3-round{
      padding:0 15px; }
    .bp3-input-group.bp3-large .bp3-input:not(:first-child){
      padding-left:40px; }
    .bp3-input-group.bp3-large .bp3-input:not(:last-child){
      padding-right:40px; }
  .bp3-input-group.bp3-small .bp3-button{
    min-width:20px;
    min-height:20px;
    margin:2px; }
  .bp3-input-group.bp3-small .bp3-tag{
    min-width:20px;
    min-height:20px;
    margin:2px; }
  .bp3-input-group.bp3-small > .bp3-icon,
  .bp3-input-group.bp3-small .bp3-input-action > .bp3-spinner{
    margin:4px; }
  .bp3-input-group.bp3-small .bp3-input{
    height:24px;
    padding-right:8px;
    padding-left:8px;
    line-height:24px;
    font-size:12px; }
    .bp3-input-group.bp3-small .bp3-input[type="search"], .bp3-input-group.bp3-small .bp3-input.bp3-round{
      padding:0 12px; }
    .bp3-input-group.bp3-small .bp3-input:not(:first-child){
      padding-left:24px; }
    .bp3-input-group.bp3-small .bp3-input:not(:last-child){
      padding-right:24px; }
  .bp3-input-group.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-input-group.bp3-round .bp3-button,
  .bp3-input-group.bp3-round .bp3-input,
  .bp3-input-group.bp3-round .bp3-tag{
    border-radius:30px; }
  .bp3-dark .bp3-input-group .bp3-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-input-group.bp3-disabled .bp3-icon{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-input-group.bp3-intent-primary .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input-group.bp3-intent-primary .bp3-input:disabled, .bp3-input-group.bp3-intent-primary .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-primary > .bp3-icon{
    color:#106ba3; }
    .bp3-dark .bp3-input-group.bp3-intent-primary > .bp3-icon{
      color:#48aff0; }
  .bp3-input-group.bp3-intent-success .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input-group.bp3-intent-success .bp3-input:disabled, .bp3-input-group.bp3-intent-success .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-success > .bp3-icon{
    color:#0d8050; }
    .bp3-dark .bp3-input-group.bp3-intent-success > .bp3-icon{
      color:#3dcc91; }
  .bp3-input-group.bp3-intent-warning .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input-group.bp3-intent-warning .bp3-input:disabled, .bp3-input-group.bp3-intent-warning .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-warning > .bp3-icon{
    color:#bf7326; }
    .bp3-dark .bp3-input-group.bp3-intent-warning > .bp3-icon{
      color:#ffb366; }
  .bp3-input-group.bp3-intent-danger .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input-group.bp3-intent-danger .bp3-input:disabled, .bp3-input-group.bp3-intent-danger .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-danger > .bp3-icon{
    color:#c23030; }
    .bp3-dark .bp3-input-group.bp3-intent-danger > .bp3-icon{
      color:#ff7373; }
.bp3-input{
  outline:none;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  height:30px;
  padding:0 10px;
  vertical-align:middle;
  line-height:30px;
  color:#182026;
  font-size:14px;
  font-weight:400;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none; }
  .bp3-input::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input:focus, .bp3-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-input[type="search"], .bp3-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-input:disabled, .bp3-input.bp3-disabled{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(206, 217, 224, 0.5);
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6);
    resize:none; }
  .bp3-input.bp3-large{
    height:40px;
    line-height:40px;
    font-size:16px; }
    .bp3-input.bp3-large[type="search"], .bp3-input.bp3-large.bp3-round{
      padding:0 15px; }
  .bp3-input.bp3-small{
    height:24px;
    padding-right:8px;
    padding-left:8px;
    line-height:24px;
    font-size:12px; }
    .bp3-input.bp3-small[type="search"], .bp3-input.bp3-small.bp3-round{
      padding:0 12px; }
  .bp3-input.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-dark .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#f5f8fa; }
    .bp3-dark .bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input:disabled, .bp3-dark .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      color:rgba(167, 182, 194, 0.6); }
  .bp3-input.bp3-intent-primary{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input.bp3-intent-primary:disabled, .bp3-input.bp3-intent-primary.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary:focus{
        -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #137cbd;
                box-shadow:inset 0 0 0 1px #137cbd; }
      .bp3-dark .bp3-input.bp3-intent-primary:disabled, .bp3-dark .bp3-input.bp3-intent-primary.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-success{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input.bp3-intent-success:disabled, .bp3-input.bp3-intent-success.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-success{
      -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success:focus{
        -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #0f9960;
                box-shadow:inset 0 0 0 1px #0f9960; }
      .bp3-dark .bp3-input.bp3-intent-success:disabled, .bp3-dark .bp3-input.bp3-intent-success.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-warning{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input.bp3-intent-warning:disabled, .bp3-input.bp3-intent-warning.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning:focus{
        -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #d9822b;
                box-shadow:inset 0 0 0 1px #d9822b; }
      .bp3-dark .bp3-input.bp3-intent-warning:disabled, .bp3-dark .bp3-input.bp3-intent-warning.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-danger{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input.bp3-intent-danger:disabled, .bp3-input.bp3-intent-danger.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger:focus{
        -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #db3737;
                box-shadow:inset 0 0 0 1px #db3737; }
      .bp3-dark .bp3-input.bp3-intent-danger:disabled, .bp3-dark .bp3-input.bp3-intent-danger.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input::-ms-clear{
    display:none; }
textarea.bp3-input{
  max-width:100%;
  padding:10px; }
  textarea.bp3-input, textarea.bp3-input.bp3-large, textarea.bp3-input.bp3-small{
    height:auto;
    line-height:inherit; }
  textarea.bp3-input.bp3-small{
    padding:8px; }
  .bp3-dark textarea.bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#f5f8fa; }
    .bp3-dark textarea.bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input:disabled, .bp3-dark textarea.bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      color:rgba(167, 182, 194, 0.6); }
label.bp3-label{
  display:block;
  margin-top:0;
  margin-bottom:15px; }
  label.bp3-label .bp3-html-select,
  label.bp3-label .bp3-input,
  label.bp3-label .bp3-select,
  label.bp3-label .bp3-slider,
  label.bp3-label .bp3-popover-wrapper{
    display:block;
    margin-top:5px;
    text-transform:none; }
  label.bp3-label .bp3-button-group{
    margin-top:5px; }
  label.bp3-label .bp3-select select,
  label.bp3-label .bp3-html-select select{
    width:100%;
    vertical-align:top;
    font-weight:400; }
  label.bp3-label.bp3-disabled,
  label.bp3-label.bp3-disabled .bp3-text-muted{
    color:rgba(92, 112, 128, 0.6); }
  label.bp3-label.bp3-inline{
    line-height:30px; }
    label.bp3-label.bp3-inline .bp3-html-select,
    label.bp3-label.bp3-inline .bp3-input,
    label.bp3-label.bp3-inline .bp3-input-group,
    label.bp3-label.bp3-inline .bp3-select,
    label.bp3-label.bp3-inline .bp3-popover-wrapper{
      display:inline-block;
      margin:0 0 0 5px;
      vertical-align:top; }
    label.bp3-label.bp3-inline .bp3-button-group{
      margin:0 0 0 5px; }
    label.bp3-label.bp3-inline .bp3-input-group .bp3-input{
      margin-left:0; }
    label.bp3-label.bp3-inline.bp3-large{
      line-height:40px; }
  label.bp3-label:not(.bp3-inline) .bp3-popover-target{
    display:block; }
  .bp3-dark label.bp3-label{
    color:#f5f8fa; }
    .bp3-dark label.bp3-label.bp3-disabled,
    .bp3-dark label.bp3-label.bp3-disabled .bp3-text-muted{
      color:rgba(167, 182, 194, 0.6); }
.bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button{
  -webkit-box-flex:1;
      -ms-flex:1 1 14px;
          flex:1 1 14px;
  width:30px;
  min-height:0;
  padding:0; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:first-child{
    border-radius:0 3px 0 0; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:last-child{
    border-radius:0 0 3px 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:first-child{
  border-radius:3px 0 0 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:last-child{
  border-radius:0 0 0 3px; }

.bp3-numeric-input.bp3-large .bp3-button-group.bp3-vertical > .bp3-button{
  width:40px; }

form{
  display:block; }
.bp3-html-select select,
.bp3-select select{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  padding:5px 10px;
  vertical-align:middle;
  text-align:left;
  font-size:14px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  color:#182026;
  border-radius:3px;
  width:100%;
  height:30px;
  padding:0 25px 0 10px;
  -moz-appearance:none;
  -webkit-appearance:none; }
  .bp3-html-select select > *, .bp3-select select > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-html-select select > .bp3-fill, .bp3-select select > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-html-select select::before,
  .bp3-select select::before, .bp3-html-select select > *, .bp3-select select > *{
    margin-right:7px; }
  .bp3-html-select select:empty::before,
  .bp3-select select:empty::before,
  .bp3-html-select select > :last-child,
  .bp3-select select > :last-child{
    margin-right:0; }
  .bp3-html-select select:hover,
  .bp3-select select:hover{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5; }
  .bp3-html-select select:active,
  .bp3-select select:active, .bp3-html-select select.bp3-active,
  .bp3-select select.bp3-active{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none; }
  .bp3-html-select select:disabled,
  .bp3-select select:disabled, .bp3-html-select select.bp3-disabled,
  .bp3-select select.bp3-disabled{
    outline:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
    .bp3-html-select select:disabled.bp3-active,
    .bp3-select select:disabled.bp3-active, .bp3-html-select select:disabled.bp3-active:hover,
    .bp3-select select:disabled.bp3-active:hover, .bp3-html-select select.bp3-disabled.bp3-active,
    .bp3-select select.bp3-disabled.bp3-active, .bp3-html-select select.bp3-disabled.bp3-active:hover,
    .bp3-select select.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }

.bp3-html-select.bp3-minimal select,
.bp3-select.bp3-minimal select{
  -webkit-box-shadow:none;
          box-shadow:none;
  background:none; }
  .bp3-html-select.bp3-minimal select:hover,
  .bp3-select.bp3-minimal select:hover{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(167, 182, 194, 0.3);
    text-decoration:none;
    color:#182026; }
  .bp3-html-select.bp3-minimal select:active,
  .bp3-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal select.bp3-active,
  .bp3-select.bp3-minimal select.bp3-active{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(115, 134, 148, 0.3);
    color:#182026; }
  .bp3-html-select.bp3-minimal select:disabled,
  .bp3-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal select:disabled:hover,
  .bp3-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal select.bp3-disabled,
  .bp3-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal select.bp3-disabled:hover,
  .bp3-select.bp3-minimal select.bp3-disabled:hover{
    background:none;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
    .bp3-html-select.bp3-minimal select:disabled.bp3-active,
    .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active{
      background:rgba(115, 134, 148, 0.3); }
  .bp3-dark .bp3-html-select.bp3-minimal select, .bp3-html-select.bp3-minimal .bp3-dark select,
  .bp3-dark .bp3-select.bp3-minimal select, .bp3-select.bp3-minimal .bp3-dark select{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none;
    color:inherit; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover, .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover{
      background:rgba(138, 155, 168, 0.15); }
    .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      background:rgba(138, 155, 168, 0.3);
      color:#f5f8fa; }
    .bp3-dark .bp3-html-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal .bp3-dark select:disabled,
    .bp3-dark .bp3-select.bp3-minimal select:disabled, .bp3-select.bp3-minimal .bp3-dark select:disabled, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select:disabled:hover, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover{
      background:none;
      cursor:not-allowed;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-html-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active{
        background:rgba(138, 155, 168, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-primary,
  .bp3-select.bp3-minimal select.bp3-intent-primary{
    color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover{
      background:rgba(19, 124, 189, 0.15);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      background:rgba(19, 124, 189, 0.3);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled{
      background:none;
      color:rgba(16, 107, 163, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active{
        background:rgba(19, 124, 189, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
      stroke:#106ba3; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary{
      color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.2);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(72, 175, 240, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-success,
  .bp3-select.bp3-minimal select.bp3-intent-success{
    color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover{
      background:rgba(15, 153, 96, 0.15);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      background:rgba(15, 153, 96, 0.3);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled{
      background:none;
      color:rgba(13, 128, 80, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active{
        background:rgba(15, 153, 96, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
      stroke:#0d8050; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success{
      color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.2);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(61, 204, 145, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-warning,
  .bp3-select.bp3-minimal select.bp3-intent-warning{
    color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover{
      background:rgba(217, 130, 43, 0.15);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      background:rgba(217, 130, 43, 0.3);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled{
      background:none;
      color:rgba(191, 115, 38, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active{
        background:rgba(217, 130, 43, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
      stroke:#bf7326; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning{
      color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.2);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(255, 179, 102, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-danger,
  .bp3-select.bp3-minimal select.bp3-intent-danger{
    color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover{
      background:rgba(219, 55, 55, 0.15);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      background:rgba(219, 55, 55, 0.3);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled{
      background:none;
      color:rgba(194, 48, 48, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active{
        background:rgba(219, 55, 55, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
      stroke:#c23030; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger{
      color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.2);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(255, 115, 115, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }

.bp3-html-select.bp3-large select,
.bp3-select.bp3-large select{
  height:40px;
  padding-right:35px;
  font-size:16px; }

.bp3-dark .bp3-html-select select, .bp3-dark .bp3-select select{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
  background-color:#394b59;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
  color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover, .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#30404d; }
  .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#202b33;
    background-image:none; }
  .bp3-dark .bp3-html-select select:disabled, .bp3-dark .bp3-select select:disabled, .bp3-dark .bp3-html-select select.bp3-disabled, .bp3-dark .bp3-select select.bp3-disabled{
    -webkit-box-shadow:none;
            box-shadow:none;
    background-color:rgba(57, 75, 89, 0.5);
    background-image:none;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-html-select select:disabled.bp3-active, .bp3-dark .bp3-select select:disabled.bp3-active, .bp3-dark .bp3-html-select select.bp3-disabled.bp3-active, .bp3-dark .bp3-select select.bp3-disabled.bp3-active{
      background:rgba(57, 75, 89, 0.7); }
  .bp3-dark .bp3-html-select select .bp3-button-spinner .bp3-spinner-head, .bp3-dark .bp3-select select .bp3-button-spinner .bp3-spinner-head{
    background:rgba(16, 22, 26, 0.5);
    stroke:#8a9ba8; }

.bp3-html-select select:disabled,
.bp3-select select:disabled{
  -webkit-box-shadow:none;
          box-shadow:none;
  background-color:rgba(206, 217, 224, 0.5);
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-html-select .bp3-icon,
.bp3-select .bp3-icon, .bp3-select::after{
  position:absolute;
  top:7px;
  right:7px;
  color:#5c7080;
  pointer-events:none; }
  .bp3-html-select .bp3-disabled.bp3-icon,
  .bp3-select .bp3-disabled.bp3-icon, .bp3-disabled.bp3-select::after{
    color:rgba(92, 112, 128, 0.6); }
.bp3-html-select,
.bp3-select{
  display:inline-block;
  position:relative;
  vertical-align:middle;
  letter-spacing:normal; }
  .bp3-html-select select::-ms-expand,
  .bp3-select select::-ms-expand{
    display:none; }
  .bp3-html-select .bp3-icon,
  .bp3-select .bp3-icon{
    color:#5c7080; }
    .bp3-html-select .bp3-icon:hover,
    .bp3-select .bp3-icon:hover{
      color:#182026; }
    .bp3-dark .bp3-html-select .bp3-icon, .bp3-dark
    .bp3-select .bp3-icon{
      color:#a7b6c2; }
      .bp3-dark .bp3-html-select .bp3-icon:hover, .bp3-dark
      .bp3-select .bp3-icon:hover{
        color:#f5f8fa; }
  .bp3-html-select.bp3-large::after,
  .bp3-html-select.bp3-large .bp3-icon,
  .bp3-select.bp3-large::after,
  .bp3-select.bp3-large .bp3-icon{
    top:12px;
    right:12px; }
  .bp3-html-select.bp3-fill,
  .bp3-html-select.bp3-fill select,
  .bp3-select.bp3-fill,
  .bp3-select.bp3-fill select{
    width:100%; }
  .bp3-dark .bp3-html-select option, .bp3-dark
  .bp3-select option{
    background-color:#30404d;
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select::after, .bp3-dark
  .bp3-select::after{
    color:#a7b6c2; }

.bp3-select::after{
  line-height:1;
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-weight:400;
  font-style:normal;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  content:""; }
.bp3-running-text table, table.bp3-html-table{
  border-spacing:0;
  font-size:14px; }
  .bp3-running-text table th, table.bp3-html-table th,
  .bp3-running-text table td,
  table.bp3-html-table td{
    padding:11px;
    vertical-align:top;
    text-align:left; }
  .bp3-running-text table th, table.bp3-html-table th{
    color:#182026;
    font-weight:600; }
  
  .bp3-running-text table td,
  table.bp3-html-table td{
    color:#182026; }
  .bp3-running-text table tbody tr:first-child th, table.bp3-html-table tbody tr:first-child th,
  .bp3-running-text table tbody tr:first-child td,
  table.bp3-html-table tbody tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-running-text table th, .bp3-running-text .bp3-dark table th, .bp3-dark table.bp3-html-table th{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table td, .bp3-running-text .bp3-dark table td, .bp3-dark table.bp3-html-table td{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table tbody tr:first-child th, .bp3-running-text .bp3-dark table tbody tr:first-child th, .bp3-dark table.bp3-html-table tbody tr:first-child th,
  .bp3-dark .bp3-running-text table tbody tr:first-child td,
  .bp3-running-text .bp3-dark table tbody tr:first-child td,
  .bp3-dark table.bp3-html-table tbody tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }

table.bp3-html-table.bp3-html-table-condensed th,
table.bp3-html-table.bp3-html-table-condensed td, table.bp3-html-table.bp3-small th,
table.bp3-html-table.bp3-small td{
  padding-top:6px;
  padding-bottom:6px; }

table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
  background:rgba(191, 204, 214, 0.15); }

table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
  -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered tbody tr td{
  -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child){
    -webkit-box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
  -webkit-box-shadow:none;
          box-shadow:none; }
  table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:not(:first-child){
    -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-interactive tbody tr:hover td{
  background-color:rgba(191, 204, 214, 0.3);
  cursor:pointer; }

table.bp3-html-table.bp3-interactive tbody tr:active td{
  background-color:rgba(191, 204, 214, 0.4); }

.bp3-dark table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
  background:rgba(92, 112, 128, 0.15); }

.bp3-dark table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
  -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }

.bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td{
  -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
          box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child){
    -webkit-box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15); }

.bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
  -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:first-child{
    -webkit-box-shadow:none;
            box-shadow:none; }

.bp3-dark table.bp3-html-table.bp3-interactive tbody tr:hover td{
  background-color:rgba(92, 112, 128, 0.3);
  cursor:pointer; }

.bp3-dark table.bp3-html-table.bp3-interactive tbody tr:active td{
  background-color:rgba(92, 112, 128, 0.4); }

.bp3-key-combo{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center; }
  .bp3-key-combo > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-key-combo > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-key-combo::before,
  .bp3-key-combo > *{
    margin-right:5px; }
  .bp3-key-combo:empty::before,
  .bp3-key-combo > :last-child{
    margin-right:0; }

.bp3-hotkey-dialog{
  top:40px;
  padding-bottom:0; }
  .bp3-hotkey-dialog .bp3-dialog-body{
    margin:0;
    padding:0; }
  .bp3-hotkey-dialog .bp3-hotkey-label{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1; }

.bp3-hotkey-column{
  margin:auto;
  max-height:80vh;
  overflow-y:auto;
  padding:30px; }
  .bp3-hotkey-column .bp3-heading{
    margin-bottom:20px; }
    .bp3-hotkey-column .bp3-heading:not(:first-child){
      margin-top:40px; }

.bp3-hotkey{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:justify;
      -ms-flex-pack:justify;
          justify-content:space-between;
  margin-right:0;
  margin-left:0; }
  .bp3-hotkey:not(:last-child){
    margin-bottom:10px; }
.bp3-icon{
  display:inline-block;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  vertical-align:text-bottom; }
  .bp3-icon:not(:empty)::before{
    content:"" !important;
    content:unset !important; }
  .bp3-icon > svg{
    display:block; }
    .bp3-icon > svg:not([fill]){
      fill:currentColor; }

.bp3-icon.bp3-intent-primary, .bp3-icon-standard.bp3-intent-primary, .bp3-icon-large.bp3-intent-primary{
  color:#106ba3; }
  .bp3-dark .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-icon-large.bp3-intent-primary{
    color:#48aff0; }

.bp3-icon.bp3-intent-success, .bp3-icon-standard.bp3-intent-success, .bp3-icon-large.bp3-intent-success{
  color:#0d8050; }
  .bp3-dark .bp3-icon.bp3-intent-success, .bp3-dark .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-icon-large.bp3-intent-success{
    color:#3dcc91; }

.bp3-icon.bp3-intent-warning, .bp3-icon-standard.bp3-intent-warning, .bp3-icon-large.bp3-intent-warning{
  color:#bf7326; }
  .bp3-dark .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-icon-large.bp3-intent-warning{
    color:#ffb366; }

.bp3-icon.bp3-intent-danger, .bp3-icon-standard.bp3-intent-danger, .bp3-icon-large.bp3-intent-danger{
  color:#c23030; }
  .bp3-dark .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-icon-large.bp3-intent-danger{
    color:#ff7373; }

span.bp3-icon-standard{
  line-height:1;
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-weight:400;
  font-style:normal;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon-large{
  line-height:1;
  font-family:"Icons20", sans-serif;
  font-size:20px;
  font-weight:400;
  font-style:normal;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon:empty{
  line-height:1;
  font-family:"Icons20";
  font-size:inherit;
  font-weight:400;
  font-style:normal; }
  span.bp3-icon:empty::before{
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased; }

.bp3-icon-add::before{
  content:""; }

.bp3-icon-add-column-left::before{
  content:""; }

.bp3-icon-add-column-right::before{
  content:""; }

.bp3-icon-add-row-bottom::before{
  content:""; }

.bp3-icon-add-row-top::before{
  content:""; }

.bp3-icon-add-to-artifact::before{
  content:""; }

.bp3-icon-add-to-folder::before{
  content:""; }

.bp3-icon-airplane::before{
  content:""; }

.bp3-icon-align-center::before{
  content:""; }

.bp3-icon-align-justify::before{
  content:""; }

.bp3-icon-align-left::before{
  content:""; }

.bp3-icon-align-right::before{
  content:""; }

.bp3-icon-alignment-bottom::before{
  content:""; }

.bp3-icon-alignment-horizontal-center::before{
  content:""; }

.bp3-icon-alignment-left::before{
  content:""; }

.bp3-icon-alignment-right::before{
  content:""; }

.bp3-icon-alignment-top::before{
  content:""; }

.bp3-icon-alignment-vertical-center::before{
  content:""; }

.bp3-icon-annotation::before{
  content:""; }

.bp3-icon-application::before{
  content:""; }

.bp3-icon-applications::before{
  content:""; }

.bp3-icon-archive::before{
  content:""; }

.bp3-icon-arrow-bottom-left::before{
  content:"↙"; }

.bp3-icon-arrow-bottom-right::before{
  content:"↘"; }

.bp3-icon-arrow-down::before{
  content:"↓"; }

.bp3-icon-arrow-left::before{
  content:"←"; }

.bp3-icon-arrow-right::before{
  content:"→"; }

.bp3-icon-arrow-top-left::before{
  content:"↖"; }

.bp3-icon-arrow-top-right::before{
  content:"↗"; }

.bp3-icon-arrow-up::before{
  content:"↑"; }

.bp3-icon-arrows-horizontal::before{
  content:"↔"; }

.bp3-icon-arrows-vertical::before{
  content:"↕"; }

.bp3-icon-asterisk::before{
  content:"*"; }

.bp3-icon-automatic-updates::before{
  content:""; }

.bp3-icon-badge::before{
  content:""; }

.bp3-icon-ban-circle::before{
  content:""; }

.bp3-icon-bank-account::before{
  content:""; }

.bp3-icon-barcode::before{
  content:""; }

.bp3-icon-blank::before{
  content:""; }

.bp3-icon-blocked-person::before{
  content:""; }

.bp3-icon-bold::before{
  content:""; }

.bp3-icon-book::before{
  content:""; }

.bp3-icon-bookmark::before{
  content:""; }

.bp3-icon-box::before{
  content:""; }

.bp3-icon-briefcase::before{
  content:""; }

.bp3-icon-bring-data::before{
  content:""; }

.bp3-icon-build::before{
  content:""; }

.bp3-icon-calculator::before{
  content:""; }

.bp3-icon-calendar::before{
  content:""; }

.bp3-icon-camera::before{
  content:""; }

.bp3-icon-caret-down::before{
  content:"⌄"; }

.bp3-icon-caret-left::before{
  content:"〈"; }

.bp3-icon-caret-right::before{
  content:"〉"; }

.bp3-icon-caret-up::before{
  content:"⌃"; }

.bp3-icon-cell-tower::before{
  content:""; }

.bp3-icon-changes::before{
  content:""; }

.bp3-icon-chart::before{
  content:""; }

.bp3-icon-chat::before{
  content:""; }

.bp3-icon-chevron-backward::before{
  content:""; }

.bp3-icon-chevron-down::before{
  content:""; }

.bp3-icon-chevron-forward::before{
  content:""; }

.bp3-icon-chevron-left::before{
  content:""; }

.bp3-icon-chevron-right::before{
  content:""; }

.bp3-icon-chevron-up::before{
  content:""; }

.bp3-icon-circle::before{
  content:""; }

.bp3-icon-circle-arrow-down::before{
  content:""; }

.bp3-icon-circle-arrow-left::before{
  content:""; }

.bp3-icon-circle-arrow-right::before{
  content:""; }

.bp3-icon-circle-arrow-up::before{
  content:""; }

.bp3-icon-citation::before{
  content:""; }

.bp3-icon-clean::before{
  content:""; }

.bp3-icon-clipboard::before{
  content:""; }

.bp3-icon-cloud::before{
  content:"☁"; }

.bp3-icon-cloud-download::before{
  content:""; }

.bp3-icon-cloud-upload::before{
  content:""; }

.bp3-icon-code::before{
  content:""; }

.bp3-icon-code-block::before{
  content:""; }

.bp3-icon-cog::before{
  content:""; }

.bp3-icon-collapse-all::before{
  content:""; }

.bp3-icon-column-layout::before{
  content:""; }

.bp3-icon-comment::before{
  content:""; }

.bp3-icon-comparison::before{
  content:""; }

.bp3-icon-compass::before{
  content:""; }

.bp3-icon-compressed::before{
  content:""; }

.bp3-icon-confirm::before{
  content:""; }

.bp3-icon-console::before{
  content:""; }

.bp3-icon-contrast::before{
  content:""; }

.bp3-icon-control::before{
  content:""; }

.bp3-icon-credit-card::before{
  content:""; }

.bp3-icon-cross::before{
  content:"✗"; }

.bp3-icon-crown::before{
  content:""; }

.bp3-icon-cube::before{
  content:""; }

.bp3-icon-cube-add::before{
  content:""; }

.bp3-icon-cube-remove::before{
  content:""; }

.bp3-icon-curved-range-chart::before{
  content:""; }

.bp3-icon-cut::before{
  content:""; }

.bp3-icon-dashboard::before{
  content:""; }

.bp3-icon-data-lineage::before{
  content:""; }

.bp3-icon-database::before{
  content:""; }

.bp3-icon-delete::before{
  content:""; }

.bp3-icon-delta::before{
  content:"Δ"; }

.bp3-icon-derive-column::before{
  content:""; }

.bp3-icon-desktop::before{
  content:""; }

.bp3-icon-diagram-tree::before{
  content:""; }

.bp3-icon-direction-left::before{
  content:""; }

.bp3-icon-direction-right::before{
  content:""; }

.bp3-icon-disable::before{
  content:""; }

.bp3-icon-document::before{
  content:""; }

.bp3-icon-document-open::before{
  content:""; }

.bp3-icon-document-share::before{
  content:""; }

.bp3-icon-dollar::before{
  content:"$"; }

.bp3-icon-dot::before{
  content:"•"; }

.bp3-icon-double-caret-horizontal::before{
  content:""; }

.bp3-icon-double-caret-vertical::before{
  content:""; }

.bp3-icon-double-chevron-down::before{
  content:""; }

.bp3-icon-double-chevron-left::before{
  content:""; }

.bp3-icon-double-chevron-right::before{
  content:""; }

.bp3-icon-double-chevron-up::before{
  content:""; }

.bp3-icon-doughnut-chart::before{
  content:""; }

.bp3-icon-download::before{
  content:""; }

.bp3-icon-drag-handle-horizontal::before{
  content:""; }

.bp3-icon-drag-handle-vertical::before{
  content:""; }

.bp3-icon-draw::before{
  content:""; }

.bp3-icon-drive-time::before{
  content:""; }

.bp3-icon-duplicate::before{
  content:""; }

.bp3-icon-edit::before{
  content:"✎"; }

.bp3-icon-eject::before{
  content:"⏏"; }

.bp3-icon-endorsed::before{
  content:""; }

.bp3-icon-envelope::before{
  content:"✉"; }

.bp3-icon-equals::before{
  content:""; }

.bp3-icon-eraser::before{
  content:""; }

.bp3-icon-error::before{
  content:""; }

.bp3-icon-euro::before{
  content:"€"; }

.bp3-icon-exchange::before{
  content:""; }

.bp3-icon-exclude-row::before{
  content:""; }

.bp3-icon-expand-all::before{
  content:""; }

.bp3-icon-export::before{
  content:""; }

.bp3-icon-eye-off::before{
  content:""; }

.bp3-icon-eye-on::before{
  content:""; }

.bp3-icon-eye-open::before{
  content:""; }

.bp3-icon-fast-backward::before{
  content:""; }

.bp3-icon-fast-forward::before{
  content:""; }

.bp3-icon-feed::before{
  content:""; }

.bp3-icon-feed-subscribed::before{
  content:""; }

.bp3-icon-film::before{
  content:""; }

.bp3-icon-filter::before{
  content:""; }

.bp3-icon-filter-keep::before{
  content:""; }

.bp3-icon-filter-list::before{
  content:""; }

.bp3-icon-filter-open::before{
  content:""; }

.bp3-icon-filter-remove::before{
  content:""; }

.bp3-icon-flag::before{
  content:"⚑"; }

.bp3-icon-flame::before{
  content:""; }

.bp3-icon-flash::before{
  content:""; }

.bp3-icon-floppy-disk::before{
  content:""; }

.bp3-icon-flow-branch::before{
  content:""; }

.bp3-icon-flow-end::before{
  content:""; }

.bp3-icon-flow-linear::before{
  content:""; }

.bp3-icon-flow-review::before{
  content:""; }

.bp3-icon-flow-review-branch::before{
  content:""; }

.bp3-icon-flows::before{
  content:""; }

.bp3-icon-folder-close::before{
  content:""; }

.bp3-icon-folder-new::before{
  content:""; }

.bp3-icon-folder-open::before{
  content:""; }

.bp3-icon-folder-shared::before{
  content:""; }

.bp3-icon-folder-shared-open::before{
  content:""; }

.bp3-icon-follower::before{
  content:""; }

.bp3-icon-following::before{
  content:""; }

.bp3-icon-font::before{
  content:""; }

.bp3-icon-fork::before{
  content:""; }

.bp3-icon-form::before{
  content:""; }

.bp3-icon-full-circle::before{
  content:""; }

.bp3-icon-full-stacked-chart::before{
  content:""; }

.bp3-icon-fullscreen::before{
  content:""; }

.bp3-icon-function::before{
  content:""; }

.bp3-icon-gantt-chart::before{
  content:""; }

.bp3-icon-geolocation::before{
  content:""; }

.bp3-icon-geosearch::before{
  content:""; }

.bp3-icon-git-branch::before{
  content:""; }

.bp3-icon-git-commit::before{
  content:""; }

.bp3-icon-git-merge::before{
  content:""; }

.bp3-icon-git-new-branch::before{
  content:""; }

.bp3-icon-git-pull::before{
  content:""; }

.bp3-icon-git-push::before{
  content:""; }

.bp3-icon-git-repo::before{
  content:""; }

.bp3-icon-glass::before{
  content:""; }

.bp3-icon-globe::before{
  content:""; }

.bp3-icon-globe-network::before{
  content:""; }

.bp3-icon-graph::before{
  content:""; }

.bp3-icon-graph-remove::before{
  content:""; }

.bp3-icon-greater-than::before{
  content:""; }

.bp3-icon-greater-than-or-equal-to::before{
  content:""; }

.bp3-icon-grid::before{
  content:""; }

.bp3-icon-grid-view::before{
  content:""; }

.bp3-icon-group-objects::before{
  content:""; }

.bp3-icon-grouped-bar-chart::before{
  content:""; }

.bp3-icon-hand::before{
  content:""; }

.bp3-icon-hand-down::before{
  content:""; }

.bp3-icon-hand-left::before{
  content:""; }

.bp3-icon-hand-right::before{
  content:""; }

.bp3-icon-hand-up::before{
  content:""; }

.bp3-icon-header::before{
  content:""; }

.bp3-icon-header-one::before{
  content:""; }

.bp3-icon-header-two::before{
  content:""; }

.bp3-icon-headset::before{
  content:""; }

.bp3-icon-heart::before{
  content:"♥"; }

.bp3-icon-heart-broken::before{
  content:""; }

.bp3-icon-heat-grid::before{
  content:""; }

.bp3-icon-heatmap::before{
  content:""; }

.bp3-icon-help::before{
  content:"?"; }

.bp3-icon-helper-management::before{
  content:""; }

.bp3-icon-highlight::before{
  content:""; }

.bp3-icon-history::before{
  content:""; }

.bp3-icon-home::before{
  content:"⌂"; }

.bp3-icon-horizontal-bar-chart::before{
  content:""; }

.bp3-icon-horizontal-bar-chart-asc::before{
  content:""; }

.bp3-icon-horizontal-bar-chart-desc::before{
  content:""; }

.bp3-icon-horizontal-distribution::before{
  content:""; }

.bp3-icon-id-number::before{
  content:""; }

.bp3-icon-image-rotate-left::before{
  content:""; }

.bp3-icon-image-rotate-right::before{
  content:""; }

.bp3-icon-import::before{
  content:""; }

.bp3-icon-inbox::before{
  content:""; }

.bp3-icon-inbox-filtered::before{
  content:""; }

.bp3-icon-inbox-geo::before{
  content:""; }

.bp3-icon-inbox-search::before{
  content:""; }

.bp3-icon-inbox-update::before{
  content:""; }

.bp3-icon-info-sign::before{
  content:"ℹ"; }

.bp3-icon-inheritance::before{
  content:""; }

.bp3-icon-inner-join::before{
  content:""; }

.bp3-icon-insert::before{
  content:""; }

.bp3-icon-intersection::before{
  content:""; }

.bp3-icon-ip-address::before{
  content:""; }

.bp3-icon-issue::before{
  content:""; }

.bp3-icon-issue-closed::before{
  content:""; }

.bp3-icon-issue-new::before{
  content:""; }

.bp3-icon-italic::before{
  content:""; }

.bp3-icon-join-table::before{
  content:""; }

.bp3-icon-key::before{
  content:""; }

.bp3-icon-key-backspace::before{
  content:""; }

.bp3-icon-key-command::before{
  content:""; }

.bp3-icon-key-control::before{
  content:""; }

.bp3-icon-key-delete::before{
  content:""; }

.bp3-icon-key-enter::before{
  content:""; }

.bp3-icon-key-escape::before{
  content:""; }

.bp3-icon-key-option::before{
  content:""; }

.bp3-icon-key-shift::before{
  content:""; }

.bp3-icon-key-tab::before{
  content:""; }

.bp3-icon-known-vehicle::before{
  content:""; }

.bp3-icon-label::before{
  content:""; }

.bp3-icon-layer::before{
  content:""; }

.bp3-icon-layers::before{
  content:""; }

.bp3-icon-layout::before{
  content:""; }

.bp3-icon-layout-auto::before{
  content:""; }

.bp3-icon-layout-balloon::before{
  content:""; }

.bp3-icon-layout-circle::before{
  content:""; }

.bp3-icon-layout-grid::before{
  content:""; }

.bp3-icon-layout-group-by::before{
  content:""; }

.bp3-icon-layout-hierarchy::before{
  content:""; }

.bp3-icon-layout-linear::before{
  content:""; }

.bp3-icon-layout-skew-grid::before{
  content:""; }

.bp3-icon-layout-sorted-clusters::before{
  content:""; }

.bp3-icon-learning::before{
  content:""; }

.bp3-icon-left-join::before{
  content:""; }

.bp3-icon-less-than::before{
  content:""; }

.bp3-icon-less-than-or-equal-to::before{
  content:""; }

.bp3-icon-lifesaver::before{
  content:""; }

.bp3-icon-lightbulb::before{
  content:""; }

.bp3-icon-link::before{
  content:""; }

.bp3-icon-list::before{
  content:"☰"; }

.bp3-icon-list-columns::before{
  content:""; }

.bp3-icon-list-detail-view::before{
  content:""; }

.bp3-icon-locate::before{
  content:""; }

.bp3-icon-lock::before{
  content:""; }

.bp3-icon-log-in::before{
  content:""; }

.bp3-icon-log-out::before{
  content:""; }

.bp3-icon-manual::before{
  content:""; }

.bp3-icon-manually-entered-data::before{
  content:""; }

.bp3-icon-map::before{
  content:""; }

.bp3-icon-map-create::before{
  content:""; }

.bp3-icon-map-marker::before{
  content:""; }

.bp3-icon-maximize::before{
  content:""; }

.bp3-icon-media::before{
  content:""; }

.bp3-icon-menu::before{
  content:""; }

.bp3-icon-menu-closed::before{
  content:""; }

.bp3-icon-menu-open::before{
  content:""; }

.bp3-icon-merge-columns::before{
  content:""; }

.bp3-icon-merge-links::before{
  content:""; }

.bp3-icon-minimize::before{
  content:""; }

.bp3-icon-minus::before{
  content:"−"; }

.bp3-icon-mobile-phone::before{
  content:""; }

.bp3-icon-mobile-video::before{
  content:""; }

.bp3-icon-moon::before{
  content:""; }

.bp3-icon-more::before{
  content:""; }

.bp3-icon-mountain::before{
  content:""; }

.bp3-icon-move::before{
  content:""; }

.bp3-icon-mugshot::before{
  content:""; }

.bp3-icon-multi-select::before{
  content:""; }

.bp3-icon-music::before{
  content:""; }

.bp3-icon-new-drawing::before{
  content:""; }

.bp3-icon-new-grid-item::before{
  content:""; }

.bp3-icon-new-layer::before{
  content:""; }

.bp3-icon-new-layers::before{
  content:""; }

.bp3-icon-new-link::before{
  content:""; }

.bp3-icon-new-object::before{
  content:""; }

.bp3-icon-new-person::before{
  content:""; }

.bp3-icon-new-prescription::before{
  content:""; }

.bp3-icon-new-text-box::before{
  content:""; }

.bp3-icon-ninja::before{
  content:""; }

.bp3-icon-not-equal-to::before{
  content:""; }

.bp3-icon-notifications::before{
  content:""; }

.bp3-icon-notifications-updated::before{
  content:""; }

.bp3-icon-numbered-list::before{
  content:""; }

.bp3-icon-numerical::before{
  content:""; }

.bp3-icon-office::before{
  content:""; }

.bp3-icon-offline::before{
  content:""; }

.bp3-icon-oil-field::before{
  content:""; }

.bp3-icon-one-column::before{
  content:""; }

.bp3-icon-outdated::before{
  content:""; }

.bp3-icon-page-layout::before{
  content:""; }

.bp3-icon-panel-stats::before{
  content:""; }

.bp3-icon-panel-table::before{
  content:""; }

.bp3-icon-paperclip::before{
  content:""; }

.bp3-icon-paragraph::before{
  content:""; }

.bp3-icon-path::before{
  content:""; }

.bp3-icon-path-search::before{
  content:""; }

.bp3-icon-pause::before{
  content:""; }

.bp3-icon-people::before{
  content:""; }

.bp3-icon-percentage::before{
  content:""; }

.bp3-icon-person::before{
  content:""; }

.bp3-icon-phone::before{
  content:"☎"; }

.bp3-icon-pie-chart::before{
  content:""; }

.bp3-icon-pin::before{
  content:""; }

.bp3-icon-pivot::before{
  content:""; }

.bp3-icon-pivot-table::before{
  content:""; }

.bp3-icon-play::before{
  content:""; }

.bp3-icon-plus::before{
  content:"+"; }

.bp3-icon-polygon-filter::before{
  content:""; }

.bp3-icon-power::before{
  content:""; }

.bp3-icon-predictive-analysis::before{
  content:""; }

.bp3-icon-prescription::before{
  content:""; }

.bp3-icon-presentation::before{
  content:""; }

.bp3-icon-print::before{
  content:"⎙"; }

.bp3-icon-projects::before{
  content:""; }

.bp3-icon-properties::before{
  content:""; }

.bp3-icon-property::before{
  content:""; }

.bp3-icon-publish-function::before{
  content:""; }

.bp3-icon-pulse::before{
  content:""; }

.bp3-icon-random::before{
  content:""; }

.bp3-icon-record::before{
  content:""; }

.bp3-icon-redo::before{
  content:""; }

.bp3-icon-refresh::before{
  content:""; }

.bp3-icon-regression-chart::before{
  content:""; }

.bp3-icon-remove::before{
  content:""; }

.bp3-icon-remove-column::before{
  content:""; }

.bp3-icon-remove-column-left::before{
  content:""; }

.bp3-icon-remove-column-right::before{
  content:""; }

.bp3-icon-remove-row-bottom::before{
  content:""; }

.bp3-icon-remove-row-top::before{
  content:""; }

.bp3-icon-repeat::before{
  content:""; }

.bp3-icon-reset::before{
  content:""; }

.bp3-icon-resolve::before{
  content:""; }

.bp3-icon-rig::before{
  content:""; }

.bp3-icon-right-join::before{
  content:""; }

.bp3-icon-ring::before{
  content:""; }

.bp3-icon-rotate-document::before{
  content:""; }

.bp3-icon-rotate-page::before{
  content:""; }

.bp3-icon-satellite::before{
  content:""; }

.bp3-icon-saved::before{
  content:""; }

.bp3-icon-scatter-plot::before{
  content:""; }

.bp3-icon-search::before{
  content:""; }

.bp3-icon-search-around::before{
  content:""; }

.bp3-icon-search-template::before{
  content:""; }

.bp3-icon-search-text::before{
  content:""; }

.bp3-icon-segmented-control::before{
  content:""; }

.bp3-icon-select::before{
  content:""; }

.bp3-icon-selection::before{
  content:"⦿"; }

.bp3-icon-send-to::before{
  content:""; }

.bp3-icon-send-to-graph::before{
  content:""; }

.bp3-icon-send-to-map::before{
  content:""; }

.bp3-icon-series-add::before{
  content:""; }

.bp3-icon-series-configuration::before{
  content:""; }

.bp3-icon-series-derived::before{
  content:""; }

.bp3-icon-series-filtered::before{
  content:""; }

.bp3-icon-series-search::before{
  content:""; }

.bp3-icon-settings::before{
  content:""; }

.bp3-icon-share::before{
  content:""; }

.bp3-icon-shield::before{
  content:""; }

.bp3-icon-shop::before{
  content:""; }

.bp3-icon-shopping-cart::before{
  content:""; }

.bp3-icon-signal-search::before{
  content:""; }

.bp3-icon-sim-card::before{
  content:""; }

.bp3-icon-slash::before{
  content:""; }

.bp3-icon-small-cross::before{
  content:""; }

.bp3-icon-small-minus::before{
  content:""; }

.bp3-icon-small-plus::before{
  content:""; }

.bp3-icon-small-tick::before{
  content:""; }

.bp3-icon-snowflake::before{
  content:""; }

.bp3-icon-social-media::before{
  content:""; }

.bp3-icon-sort::before{
  content:""; }

.bp3-icon-sort-alphabetical::before{
  content:""; }

.bp3-icon-sort-alphabetical-desc::before{
  content:""; }

.bp3-icon-sort-asc::before{
  content:""; }

.bp3-icon-sort-desc::before{
  content:""; }

.bp3-icon-sort-numerical::before{
  content:""; }

.bp3-icon-sort-numerical-desc::before{
  content:""; }

.bp3-icon-split-columns::before{
  content:""; }

.bp3-icon-square::before{
  content:""; }

.bp3-icon-stacked-chart::before{
  content:""; }

.bp3-icon-star::before{
  content:"★"; }

.bp3-icon-star-empty::before{
  content:"☆"; }

.bp3-icon-step-backward::before{
  content:""; }

.bp3-icon-step-chart::before{
  content:""; }

.bp3-icon-step-forward::before{
  content:""; }

.bp3-icon-stop::before{
  content:""; }

.bp3-icon-stopwatch::before{
  content:""; }

.bp3-icon-strikethrough::before{
  content:""; }

.bp3-icon-style::before{
  content:""; }

.bp3-icon-swap-horizontal::before{
  content:""; }

.bp3-icon-swap-vertical::before{
  content:""; }

.bp3-icon-symbol-circle::before{
  content:""; }

.bp3-icon-symbol-cross::before{
  content:""; }

.bp3-icon-symbol-diamond::before{
  content:""; }

.bp3-icon-symbol-square::before{
  content:""; }

.bp3-icon-symbol-triangle-down::before{
  content:""; }

.bp3-icon-symbol-triangle-up::before{
  content:""; }

.bp3-icon-tag::before{
  content:""; }

.bp3-icon-take-action::before{
  content:""; }

.bp3-icon-taxi::before{
  content:""; }

.bp3-icon-text-highlight::before{
  content:""; }

.bp3-icon-th::before{
  content:""; }

.bp3-icon-th-derived::before{
  content:""; }

.bp3-icon-th-disconnect::before{
  content:""; }

.bp3-icon-th-filtered::before{
  content:""; }

.bp3-icon-th-list::before{
  content:""; }

.bp3-icon-thumbs-down::before{
  content:""; }

.bp3-icon-thumbs-up::before{
  content:""; }

.bp3-icon-tick::before{
  content:"✓"; }

.bp3-icon-tick-circle::before{
  content:""; }

.bp3-icon-time::before{
  content:"⏲"; }

.bp3-icon-timeline-area-chart::before{
  content:""; }

.bp3-icon-timeline-bar-chart::before{
  content:""; }

.bp3-icon-timeline-events::before{
  content:""; }

.bp3-icon-timeline-line-chart::before{
  content:""; }

.bp3-icon-tint::before{
  content:""; }

.bp3-icon-torch::before{
  content:""; }

.bp3-icon-tractor::before{
  content:""; }

.bp3-icon-train::before{
  content:""; }

.bp3-icon-translate::before{
  content:""; }

.bp3-icon-trash::before{
  content:""; }

.bp3-icon-tree::before{
  content:""; }

.bp3-icon-trending-down::before{
  content:""; }

.bp3-icon-trending-up::before{
  content:""; }

.bp3-icon-truck::before{
  content:""; }

.bp3-icon-two-columns::before{
  content:""; }

.bp3-icon-unarchive::before{
  content:""; }

.bp3-icon-underline::before{
  content:"⎁"; }

.bp3-icon-undo::before{
  content:"⎌"; }

.bp3-icon-ungroup-objects::before{
  content:""; }

.bp3-icon-unknown-vehicle::before{
  content:""; }

.bp3-icon-unlock::before{
  content:""; }

.bp3-icon-unpin::before{
  content:""; }

.bp3-icon-unresolve::before{
  content:""; }

.bp3-icon-updated::before{
  content:""; }

.bp3-icon-upload::before{
  content:""; }

.bp3-icon-user::before{
  content:""; }

.bp3-icon-variable::before{
  content:""; }

.bp3-icon-vertical-bar-chart-asc::before{
  content:""; }

.bp3-icon-vertical-bar-chart-desc::before{
  content:""; }

.bp3-icon-vertical-distribution::before{
  content:""; }

.bp3-icon-video::before{
  content:""; }

.bp3-icon-volume-down::before{
  content:""; }

.bp3-icon-volume-off::before{
  content:""; }

.bp3-icon-volume-up::before{
  content:""; }

.bp3-icon-walk::before{
  content:""; }

.bp3-icon-warning-sign::before{
  content:""; }

.bp3-icon-waterfall-chart::before{
  content:""; }

.bp3-icon-widget::before{
  content:""; }

.bp3-icon-widget-button::before{
  content:""; }

.bp3-icon-widget-footer::before{
  content:""; }

.bp3-icon-widget-header::before{
  content:""; }

.bp3-icon-wrench::before{
  content:""; }

.bp3-icon-zoom-in::before{
  content:""; }

.bp3-icon-zoom-out::before{
  content:""; }

.bp3-icon-zoom-to-fit::before{
  content:""; }
.bp3-submenu > .bp3-popover-wrapper{
  display:block; }

.bp3-submenu .bp3-popover-target{
  display:block; }

.bp3-submenu.bp3-popover{
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0 5px; }
  .bp3-submenu.bp3-popover > .bp3-popover-content{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-submenu.bp3-popover, .bp3-submenu.bp3-popover.bp3-dark{
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-dark .bp3-submenu.bp3-popover > .bp3-popover-content, .bp3-submenu.bp3-popover.bp3-dark > .bp3-popover-content{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
.bp3-menu{
  margin:0;
  border-radius:3px;
  background:#ffffff;
  min-width:180px;
  padding:5px;
  list-style:none;
  text-align:left;
  color:#182026; }

.bp3-menu-divider{
  display:block;
  margin:5px;
  border-top:1px solid rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-menu-divider{
    border-top-color:rgba(255, 255, 255, 0.15); }

.bp3-menu-item{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  border-radius:2px;
  padding:5px 7px;
  text-decoration:none;
  line-height:20px;
  color:inherit;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-menu-item > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-menu-item > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-menu-item::before,
  .bp3-menu-item > *{
    margin-right:7px; }
  .bp3-menu-item:empty::before,
  .bp3-menu-item > :last-child{
    margin-right:0; }
  .bp3-menu-item > .bp3-fill{
    word-break:break-word; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    background-color:rgba(167, 182, 194, 0.3);
    cursor:pointer;
    text-decoration:none; }
  .bp3-menu-item.bp3-disabled{
    background-color:inherit;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-dark .bp3-menu-item{
    color:inherit; }
    .bp3-dark .bp3-menu-item:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
      background-color:rgba(138, 155, 168, 0.15);
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-disabled{
      background-color:inherit;
      color:rgba(167, 182, 194, 0.6); }
  .bp3-menu-item.bp3-intent-primary{
    color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-primary::before, .bp3-menu-item.bp3-intent-primary::after,
    .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
      color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary.bp3-active{
      background-color:#137cbd; }
    .bp3-menu-item.bp3-intent-primary:active{
      background-color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary:active, .bp3-menu-item.bp3-intent-primary:active::before, .bp3-menu-item.bp3-intent-primary:active::after,
    .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-menu-item.bp3-intent-primary.bp3-active::after,
    .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-success{
    color:#0d8050; }
    .bp3-menu-item.bp3-intent-success .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-success::before, .bp3-menu-item.bp3-intent-success::after,
    .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
      color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success.bp3-active{
      background-color:#0f9960; }
    .bp3-menu-item.bp3-intent-success:active{
      background-color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-menu-item.bp3-intent-success:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success:active, .bp3-menu-item.bp3-intent-success:active::before, .bp3-menu-item.bp3-intent-success:active::after,
    .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-menu-item.bp3-intent-success.bp3-active::after,
    .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-warning{
    color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-warning::before, .bp3-menu-item.bp3-intent-warning::after,
    .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
      color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning.bp3-active{
      background-color:#d9822b; }
    .bp3-menu-item.bp3-intent-warning:active{
      background-color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning:active, .bp3-menu-item.bp3-intent-warning:active::before, .bp3-menu-item.bp3-intent-warning:active::after,
    .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-menu-item.bp3-intent-warning.bp3-active::after,
    .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-danger{
    color:#c23030; }
    .bp3-menu-item.bp3-intent-danger .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-danger::before, .bp3-menu-item.bp3-intent-danger::after,
    .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
      color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger.bp3-active{
      background-color:#db3737; }
    .bp3-menu-item.bp3-intent-danger:active{
      background-color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger:active, .bp3-menu-item.bp3-intent-danger:active::before, .bp3-menu-item.bp3-intent-danger:active::after,
    .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-menu-item.bp3-intent-danger.bp3-active::after,
    .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item::before{
    line-height:1;
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-weight:400;
    font-style:normal;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    margin-right:7px; }
  .bp3-menu-item::before,
  .bp3-menu-item > .bp3-icon{
    margin-top:2px;
    color:#5c7080; }
  .bp3-menu-item .bp3-menu-item-label{
    color:#5c7080; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    color:inherit; }
  .bp3-menu-item.bp3-active, .bp3-menu-item:active{
    background-color:rgba(115, 134, 148, 0.3); }
  .bp3-menu-item.bp3-disabled{
    outline:none !important;
    background-color:inherit !important;
    cursor:not-allowed !important;
    color:rgba(92, 112, 128, 0.6) !important; }
    .bp3-menu-item.bp3-disabled::before,
    .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-large .bp3-menu-item{
    padding:9px 7px;
    line-height:22px;
    font-size:16px; }
    .bp3-large .bp3-menu-item .bp3-icon{
      margin-top:3px; }
    .bp3-large .bp3-menu-item::before{
      line-height:1;
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-weight:400;
      font-style:normal;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      margin-top:1px;
      margin-right:10px; }

button.bp3-menu-item{
  border:none;
  background:none;
  width:100%;
  text-align:left; }
.bp3-menu-header{
  display:block;
  margin:5px;
  border-top:1px solid rgba(16, 22, 26, 0.15);
  cursor:default;
  padding-left:2px; }
  .bp3-dark .bp3-menu-header{
    border-top-color:rgba(255, 255, 255, 0.15); }
  .bp3-menu-header:first-of-type{
    border-top:none; }
  .bp3-menu-header > h6{
    color:#182026;
    font-weight:600;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    margin:0;
    padding:10px 7px 0 1px;
    line-height:17px; }
    .bp3-dark .bp3-menu-header > h6{
      color:#f5f8fa; }
  .bp3-menu-header:first-of-type > h6{
    padding-top:0; }
  .bp3-large .bp3-menu-header > h6{
    padding-top:15px;
    padding-bottom:5px;
    font-size:18px; }
  .bp3-large .bp3-menu-header:first-of-type > h6{
    padding-top:0; }

.bp3-dark .bp3-menu{
  background:#30404d;
  color:#f5f8fa; }

.bp3-dark .bp3-menu-item.bp3-intent-primary{
  color:#48aff0; }
  .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-icon{
    color:inherit; }
  .bp3-dark .bp3-menu-item.bp3-intent-primary::before, .bp3-dark .bp3-menu-item.bp3-intent-primary::after,
  .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
    color:#48aff0; }
  .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active{
    background-color:#137cbd; }
  .bp3-dark .bp3-menu-item.bp3-intent-primary:active{
    background-color:#106ba3; }
  .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
  .bp3-dark .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
  .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label,
  .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary:active, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
    color:#ffffff; }

.bp3-dark .bp3-menu-item.bp3-intent-success{
  color:#3dcc91; }
  .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-icon{
    color:inherit; }
  .bp3-dark .bp3-menu-item.bp3-intent-success::before, .bp3-dark .bp3-menu-item.bp3-intent-success::after,
  .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
    color:#3dcc91; }
  .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active{
    background-color:#0f9960; }
  .bp3-dark .bp3-menu-item.bp3-intent-success:active{
    background-color:#0d8050; }
  .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
  .bp3-dark .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
  .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label,
  .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success:active, .bp3-dark .bp3-menu-item.bp3-intent-success:active::before, .bp3-dark .bp3-menu-item.bp3-intent-success:active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
    color:#ffffff; }

.bp3-dark .bp3-menu-item.bp3-intent-warning{
  color:#ffb366; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-icon{
    color:inherit; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning::before, .bp3-dark .bp3-menu-item.bp3-intent-warning::after,
  .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
    color:#ffb366; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active{
    background-color:#d9822b; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning:active{
    background-color:#bf7326; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
  .bp3-dark .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
  .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label,
  .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning:active, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
    color:#ffffff; }

.bp3-dark .bp3-menu-item.bp3-intent-danger{
  color:#ff7373; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-icon{
    color:inherit; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger::before, .bp3-dark .bp3-menu-item.bp3-intent-danger::after,
  .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
    color:#ff7373; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active{
    background-color:#db3737; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger:active{
    background-color:#c23030; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
  .bp3-dark .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
  .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label,
  .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger:active, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
    color:#ffffff; }

.bp3-dark .bp3-menu-item::before,
.bp3-dark .bp3-menu-item > .bp3-icon{
  color:#a7b6c2; }

.bp3-dark .bp3-menu-item .bp3-menu-item-label{
  color:#a7b6c2; }

.bp3-dark .bp3-menu-item.bp3-active, .bp3-dark .bp3-menu-item:active{
  background-color:rgba(138, 155, 168, 0.3); }

.bp3-dark .bp3-menu-item.bp3-disabled{
  color:rgba(167, 182, 194, 0.6) !important; }
  .bp3-dark .bp3-menu-item.bp3-disabled::before,
  .bp3-dark .bp3-menu-item.bp3-disabled > .bp3-icon,
  .bp3-dark .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
    color:rgba(167, 182, 194, 0.6) !important; }

.bp3-dark .bp3-menu-divider,
.bp3-dark .bp3-menu-header{
  border-color:rgba(255, 255, 255, 0.15); }

.bp3-dark .bp3-menu-header > h6{
  color:#f5f8fa; }

.bp3-label .bp3-menu{
  margin-top:5px; }
.bp3-navbar{
  position:relative;
  z-index:10;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  background-color:#ffffff;
  width:100%;
  height:50px;
  padding:0 15px; }
  .bp3-navbar.bp3-dark,
  .bp3-dark .bp3-navbar{
    background-color:#394b59; }
  .bp3-navbar.bp3-dark{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-navbar{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-navbar.bp3-fixed-top{
    position:fixed;
    top:0;
    right:0;
    left:0; }

.bp3-navbar-heading{
  margin-right:15px;
  font-size:16px; }

.bp3-navbar-group{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  height:50px; }
  .bp3-navbar-group.bp3-align-left{
    float:left; }
  .bp3-navbar-group.bp3-align-right{
    float:right; }

.bp3-navbar-divider{
  margin:0 10px;
  border-left:1px solid rgba(16, 22, 26, 0.15);
  height:20px; }
  .bp3-dark .bp3-navbar-divider{
    border-left-color:rgba(255, 255, 255, 0.15); }
.bp3-non-ideal-state{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  width:100%;
  height:100%;
  text-align:center; }
  .bp3-non-ideal-state > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-non-ideal-state > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-non-ideal-state::before,
  .bp3-non-ideal-state > *{
    margin-bottom:20px; }
  .bp3-non-ideal-state:empty::before,
  .bp3-non-ideal-state > :last-child{
    margin-bottom:0; }
  .bp3-non-ideal-state > *{
    max-width:400px; }

.bp3-non-ideal-state-visual{
  color:rgba(92, 112, 128, 0.6);
  font-size:60px; }
  .bp3-dark .bp3-non-ideal-state-visual{
    color:rgba(167, 182, 194, 0.6); }

.bp3-overflow-list{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:nowrap;
      flex-wrap:nowrap;
  min-width:0; }

.bp3-overflow-list-spacer{
  -ms-flex-negative:1;
      flex-shrink:1;
  width:1px; }

body.bp3-overlay-open{
  overflow:hidden; }

.bp3-overlay{
  position:static;
  top:0;
  right:0;
  bottom:0;
  left:0;
  z-index:20; }
  .bp3-overlay:not(.bp3-overlay-open){
    pointer-events:none; }
  .bp3-overlay.bp3-overlay-container{
    position:fixed;
    overflow:hidden; }
    .bp3-overlay.bp3-overlay-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-scroll-container{
    position:fixed;
    overflow:auto; }
    .bp3-overlay.bp3-overlay-scroll-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-inline{
    display:inline;
    overflow:visible; }

.bp3-overlay-content{
  position:fixed;
  z-index:20; }
  .bp3-overlay-inline .bp3-overlay-content,
  .bp3-overlay-scroll-container .bp3-overlay-content{
    position:absolute; }

.bp3-overlay-backdrop{
  position:fixed;
  top:0;
  right:0;
  bottom:0;
  left:0;
  opacity:1;
  z-index:20;
  background-color:rgba(16, 22, 26, 0.7);
  overflow:auto;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-overlay-backdrop.bp3-overlay-enter, .bp3-overlay-backdrop.bp3-overlay-appear{
    opacity:0; }
  .bp3-overlay-backdrop.bp3-overlay-enter-active, .bp3-overlay-backdrop.bp3-overlay-appear-active{
    opacity:1;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-overlay-backdrop.bp3-overlay-exit{
    opacity:1; }
  .bp3-overlay-backdrop.bp3-overlay-exit-active{
    opacity:0;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-overlay-backdrop:focus{
    outline:none; }
  .bp3-overlay-inline .bp3-overlay-backdrop{
    position:absolute; }
.bp3-panel-stack{
  position:relative;
  overflow:hidden; }

.bp3-panel-stack-header{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  z-index:1;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  height:30px; }
  .bp3-dark .bp3-panel-stack-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack-header > span{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1;
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch; }
  .bp3-panel-stack-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack-view{
  position:absolute;
  top:0;
  right:0;
  bottom:0;
  left:0;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  background-color:#ffffff;
  overflow-y:auto; }
  .bp3-dark .bp3-panel-stack-view{
    background-color:#30404d; }

.bp3-panel-stack-push .bp3-panel-stack-enter, .bp3-panel-stack-push .bp3-panel-stack-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack-push .bp3-panel-stack-enter-active, .bp3-panel-stack-push .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }

.bp3-panel-stack-push .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-push .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }

.bp3-panel-stack-pop .bp3-panel-stack-enter, .bp3-panel-stack-pop .bp3-panel-stack-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack-pop .bp3-panel-stack-enter-active, .bp3-panel-stack-pop .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }

.bp3-panel-stack-pop .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-pop .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }
.bp3-popover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1);
  display:inline-block;
  z-index:20;
  border-radius:3px; }
  .bp3-popover .bp3-popover-arrow{
    position:absolute;
    width:30px;
    height:30px; }
    .bp3-popover .bp3-popover-arrow::before{
      margin:5px;
      width:20px;
      height:20px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover{
    margin-top:-17px;
    margin-bottom:17px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
      bottom:-11px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover{
    margin-left:17px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
      left:-11px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover{
    margin-top:17px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
      top:-11px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover{
    margin-right:17px;
    margin-left:-17px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
      right:-11px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-popover > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-popover > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
    top:-0.3934px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
    right:-0.3934px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
    left:-0.3934px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
    bottom:-0.3934px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-popover .bp3-popover-content{
    background:#ffffff;
    color:inherit; }
  .bp3-popover .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-popover .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-popover .bp3-popover-arrow-fill{
    fill:#ffffff; }
  .bp3-popover-enter > .bp3-popover, .bp3-popover-appear > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3); }
  .bp3-popover-enter-active > .bp3-popover, .bp3-popover-appear-active > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-popover-exit > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-popover .bp3-popover-content{
    position:relative;
    border-radius:3px; }
  .bp3-popover.bp3-popover-content-sizing .bp3-popover-content{
    max-width:350px;
    padding:20px; }
  .bp3-popover-target + .bp3-overlay .bp3-popover.bp3-popover-content-sizing{
    width:350px; }
  .bp3-popover.bp3-minimal{
    margin:0 !important; }
    .bp3-popover.bp3-minimal .bp3-popover-arrow{
      display:none; }
    .bp3-popover.bp3-minimal.bp3-popover{
      -webkit-transform:scale(1);
              transform:scale(1); }
      .bp3-popover-enter > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-enter-active > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
        -webkit-transition-delay:0;
                transition-delay:0; }
      .bp3-popover-exit > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-exit-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
        -webkit-transition-delay:0;
                transition-delay:0; }
  .bp3-popover.bp3-dark,
  .bp3-dark .bp3-popover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-popover .bp3-popover-content{
      background:#30404d;
      color:inherit; }
    .bp3-popover.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-popover .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-popover .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-popover.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-popover .bp3-popover-arrow-fill{
      fill:#30404d; }

.bp3-popover-arrow::before{
  display:block;
  position:absolute;
  -webkit-transform:rotate(45deg);
          transform:rotate(45deg);
  border-radius:2px;
  content:""; }

.bp3-tether-pinned .bp3-popover-arrow{
  display:none; }

.bp3-popover-backdrop{
  background:rgba(255, 255, 255, 0); }

.bp3-transition-container{
  opacity:1;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  z-index:20; }
  .bp3-transition-container.bp3-popover-enter, .bp3-transition-container.bp3-popover-appear{
    opacity:0; }
  .bp3-transition-container.bp3-popover-enter-active, .bp3-transition-container.bp3-popover-appear-active{
    opacity:1;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-transition-container.bp3-popover-exit{
    opacity:1; }
  .bp3-transition-container.bp3-popover-exit-active{
    opacity:0;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-transition-container:focus{
    outline:none; }
  .bp3-transition-container.bp3-popover-leave .bp3-popover-content{
    pointer-events:none; }
  .bp3-transition-container[data-x-out-of-boundaries]{
    display:none; }

span.bp3-popover-target{
  display:inline-block; }

.bp3-popover-wrapper.bp3-fill{
  width:100%; }

.bp3-portal{
  position:absolute;
  top:0;
  right:0;
  left:0; }
@-webkit-keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }
@keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }

.bp3-progress-bar{
  display:block;
  position:relative;
  border-radius:40px;
  background:rgba(92, 112, 128, 0.2);
  width:100%;
  height:8px;
  overflow:hidden; }
  .bp3-progress-bar .bp3-progress-meter{
    position:absolute;
    border-radius:40px;
    background:linear-gradient(-45deg, rgba(255, 255, 255, 0.2) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.2) 50%, rgba(255, 255, 255, 0.2) 75%, transparent 75%);
    background-color:rgba(92, 112, 128, 0.8);
    background-size:30px 30px;
    width:100%;
    height:100%;
    -webkit-transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-progress-bar:not(.bp3-no-animation):not(.bp3-no-stripes) .bp3-progress-meter{
    animation:linear-progress-bar-stripes 300ms linear infinite reverse; }
  .bp3-progress-bar.bp3-no-stripes .bp3-progress-meter{
    background-image:none; }

.bp3-dark .bp3-progress-bar{
  background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-progress-bar .bp3-progress-meter{
    background-color:#8a9ba8; }

.bp3-progress-bar.bp3-intent-primary .bp3-progress-meter{
  background-color:#137cbd; }

.bp3-progress-bar.bp3-intent-success .bp3-progress-meter{
  background-color:#0f9960; }

.bp3-progress-bar.bp3-intent-warning .bp3-progress-meter{
  background-color:#d9822b; }

.bp3-progress-bar.bp3-intent-danger .bp3-progress-meter{
  background-color:#db3737; }
@-webkit-keyframes skeleton-glow{
  from{
    border-color:rgba(206, 217, 224, 0.2);
    background:rgba(206, 217, 224, 0.2); }
  to{
    border-color:rgba(92, 112, 128, 0.2);
    background:rgba(92, 112, 128, 0.2); } }
@keyframes skeleton-glow{
  from{
    border-color:rgba(206, 217, 224, 0.2);
    background:rgba(206, 217, 224, 0.2); }
  to{
    border-color:rgba(92, 112, 128, 0.2);
    background:rgba(92, 112, 128, 0.2); } }
.bp3-skeleton{
  border-color:rgba(206, 217, 224, 0.2) !important;
  border-radius:2px;
  -webkit-box-shadow:none !important;
          box-shadow:none !important;
  background:rgba(206, 217, 224, 0.2);
  background-clip:padding-box !important;
  cursor:default;
  color:transparent !important;
  -webkit-animation:1000ms linear infinite alternate skeleton-glow;
          animation:1000ms linear infinite alternate skeleton-glow;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-skeleton::before, .bp3-skeleton::after,
  .bp3-skeleton *{
    visibility:hidden !important; }
.bp3-slider{
  width:100%;
  min-width:150px;
  height:40px;
  position:relative;
  outline:none;
  cursor:default;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-slider:hover{
    cursor:pointer; }
  .bp3-slider:active{
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-slider.bp3-disabled{
    opacity:0.5;
    cursor:not-allowed; }
  .bp3-slider.bp3-slider-unlabeled{
    height:16px; }

.bp3-slider-track,
.bp3-slider-progress{
  top:5px;
  right:0;
  left:0;
  height:6px;
  position:absolute; }

.bp3-slider-track{
  border-radius:3px;
  overflow:hidden; }

.bp3-slider-progress{
  background:rgba(92, 112, 128, 0.2); }
  .bp3-dark .bp3-slider-progress{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-slider-progress.bp3-intent-primary{
    background-color:#137cbd; }
  .bp3-slider-progress.bp3-intent-success{
    background-color:#0f9960; }
  .bp3-slider-progress.bp3-intent-warning{
    background-color:#d9822b; }
  .bp3-slider-progress.bp3-intent-danger{
    background-color:#db3737; }

.bp3-slider-handle{
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  color:#182026;
  position:absolute;
  top:0;
  left:0;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
  cursor:pointer;
  width:16px;
  height:16px; }
  .bp3-slider-handle:hover{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5; }
  .bp3-slider-handle:active, .bp3-slider-handle.bp3-active{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none; }
  .bp3-slider-handle:disabled, .bp3-slider-handle.bp3-disabled{
    outline:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
    .bp3-slider-handle:disabled.bp3-active, .bp3-slider-handle:disabled.bp3-active:hover, .bp3-slider-handle.bp3-disabled.bp3-active, .bp3-slider-handle.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }
  .bp3-slider-handle:focus{
    z-index:1; }
  .bp3-slider-handle:hover{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5;
    z-index:2;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
    cursor:-webkit-grab;
    cursor:grab; }
  .bp3-slider-handle.bp3-active{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-disabled .bp3-slider-handle{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:#bfccd6;
    pointer-events:none; }
  .bp3-dark .bp3-slider-handle{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover, .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#30404d; }
    .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#202b33;
      background-image:none; }
    .bp3-dark .bp3-slider-handle:disabled, .bp3-dark .bp3-slider-handle.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-slider-handle:disabled.bp3-active, .bp3-dark .bp3-slider-handle.bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-slider-handle .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-slider-handle, .bp3-dark .bp3-slider-handle:hover{
      background-color:#394b59; }
    .bp3-dark .bp3-slider-handle.bp3-active{
      background-color:#293742; }
  .bp3-dark .bp3-disabled .bp3-slider-handle{
    border-color:#5c7080;
    -webkit-box-shadow:none;
            box-shadow:none;
    background:#5c7080; }
  .bp3-slider-handle .bp3-slider-label{
    margin-left:8px;
    border-radius:3px;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
    background:#394b59;
    color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle .bp3-slider-label{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
      background:#e1e8ed;
      color:#394b59; }
    .bp3-disabled .bp3-slider-handle .bp3-slider-label{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-slider-handle.bp3-start, .bp3-slider-handle.bp3-end{
    width:8px; }
  .bp3-slider-handle.bp3-start{
    border-top-right-radius:0;
    border-bottom-right-radius:0; }
  .bp3-slider-handle.bp3-end{
    margin-left:8px;
    border-top-left-radius:0;
    border-bottom-left-radius:0; }
    .bp3-slider-handle.bp3-end .bp3-slider-label{
      margin-left:0; }

.bp3-slider-label{
  -webkit-transform:translate(-50%, 20px);
          transform:translate(-50%, 20px);
  display:inline-block;
  position:absolute;
  padding:2px 5px;
  vertical-align:top;
  line-height:1;
  font-size:12px; }

.bp3-slider.bp3-vertical{
  width:40px;
  min-width:40px;
  height:150px; }
  .bp3-slider.bp3-vertical .bp3-slider-track,
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    top:0;
    bottom:0;
    left:5px;
    width:6px;
    height:auto; }
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    top:auto; }
  .bp3-slider.bp3-vertical .bp3-slider-label{
    -webkit-transform:translate(20px, 50%);
            transform:translate(20px, 50%); }
  .bp3-slider.bp3-vertical .bp3-slider-handle{
    top:auto; }
    .bp3-slider.bp3-vertical .bp3-slider-handle .bp3-slider-label{
      margin-top:-8px;
      margin-left:0; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end, .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      margin-left:0;
      width:16px;
      height:8px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      border-top-left-radius:0;
      border-bottom-right-radius:3px; }
      .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start .bp3-slider-label{
        -webkit-transform:translate(20px);
                transform:translate(20px); }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end{
      margin-bottom:8px;
      border-top-left-radius:3px;
      border-bottom-left-radius:0;
      border-bottom-right-radius:0; }

@-webkit-keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

@keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

.bp3-spinner{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  overflow:visible;
  vertical-align:middle; }
  .bp3-spinner svg{
    display:block; }
  .bp3-spinner path{
    fill-opacity:0; }
  .bp3-spinner .bp3-spinner-head{
    -webkit-transform-origin:center;
            transform-origin:center;
    -webkit-transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    stroke:rgba(92, 112, 128, 0.8);
    stroke-linecap:round; }
  .bp3-spinner .bp3-spinner-track{
    stroke:rgba(92, 112, 128, 0.2); }

.bp3-spinner-animation{
  -webkit-animation:pt-spinner-animation 500ms linear infinite;
          animation:pt-spinner-animation 500ms linear infinite; }
  .bp3-no-spin > .bp3-spinner-animation{
    -webkit-animation:none;
            animation:none; }

.bp3-dark .bp3-spinner .bp3-spinner-head{
  stroke:#8a9ba8; }

.bp3-dark .bp3-spinner .bp3-spinner-track{
  stroke:rgba(16, 22, 26, 0.5); }

.bp3-spinner.bp3-intent-primary .bp3-spinner-head{
  stroke:#137cbd; }

.bp3-spinner.bp3-intent-success .bp3-spinner-head{
  stroke:#0f9960; }

.bp3-spinner.bp3-intent-warning .bp3-spinner-head{
  stroke:#d9822b; }

.bp3-spinner.bp3-intent-danger .bp3-spinner-head{
  stroke:#db3737; }
.bp3-tabs.bp3-vertical{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-tabs.bp3-vertical > .bp3-tab-list{
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column;
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab{
      border-radius:3px;
      width:100%;
      padding:0 10px; }
      .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab[aria-selected="true"]{
        -webkit-box-shadow:none;
                box-shadow:none;
        background-color:rgba(19, 124, 189, 0.2); }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab-indicator-wrapper .bp3-tab-indicator{
      top:0;
      right:0;
      bottom:0;
      left:0;
      border-radius:3px;
      background-color:rgba(19, 124, 189, 0.2);
      height:auto; }
  .bp3-tabs.bp3-vertical > .bp3-tab-panel{
    margin-top:0;
    padding-left:20px; }

.bp3-tab-list{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  -webkit-box-align:end;
      -ms-flex-align:end;
          align-items:flex-end;
  position:relative;
  margin:0;
  border:none;
  padding:0;
  list-style:none; }
  .bp3-tab-list > *:not(:last-child){
    margin-right:20px; }

.bp3-tab{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  position:relative;
  cursor:pointer;
  max-width:100%;
  vertical-align:top;
  line-height:30px;
  color:#182026;
  font-size:14px; }
  .bp3-tab a{
    display:block;
    text-decoration:none;
    color:inherit; }
  .bp3-tab-indicator-wrapper ~ .bp3-tab{
    -webkit-box-shadow:none !important;
            box-shadow:none !important;
    background-color:transparent !important; }
  .bp3-tab[aria-disabled="true"]{
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-tab[aria-selected="true"]{
    border-radius:0;
    -webkit-box-shadow:inset 0 -3px 0 #106ba3;
            box-shadow:inset 0 -3px 0 #106ba3; }
  .bp3-tab[aria-selected="true"], .bp3-tab:not([aria-disabled="true"]):hover{
    color:#106ba3; }
  .bp3-tab:focus{
    -moz-outline-radius:0; }
  .bp3-large > .bp3-tab{
    line-height:40px;
    font-size:16px; }

.bp3-tab-panel{
  margin-top:20px; }
  .bp3-tab-panel[aria-hidden="true"]{
    display:none; }

.bp3-tab-indicator-wrapper{
  position:absolute;
  top:0;
  left:0;
  -webkit-transform:translateX(0), translateY(0);
          transform:translateX(0), translateY(0);
  -webkit-transition:height, width, -webkit-transform;
  transition:height, width, -webkit-transform;
  transition:height, transform, width;
  transition:height, transform, width, -webkit-transform;
  -webkit-transition-duration:200ms;
          transition-duration:200ms;
  -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
          transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
  pointer-events:none; }
  .bp3-tab-indicator-wrapper .bp3-tab-indicator{
    position:absolute;
    right:0;
    bottom:0;
    left:0;
    background-color:#106ba3;
    height:3px; }
  .bp3-tab-indicator-wrapper.bp3-no-animation{
    -webkit-transition:none;
    transition:none; }

.bp3-dark .bp3-tab{
  color:#f5f8fa; }
  .bp3-dark .bp3-tab[aria-disabled="true"]{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tab[aria-selected="true"]{
    -webkit-box-shadow:inset 0 -3px 0 #48aff0;
            box-shadow:inset 0 -3px 0 #48aff0; }
  .bp3-dark .bp3-tab[aria-selected="true"], .bp3-dark .bp3-tab:not([aria-disabled="true"]):hover{
    color:#48aff0; }

.bp3-dark .bp3-tab-indicator{
  background-color:#48aff0; }

.bp3-flex-expander{
  -webkit-box-flex:1;
      -ms-flex:1 1;
          flex:1 1; }
.bp3-tag{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  position:relative;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:none;
          box-shadow:none;
  background-color:#5c7080;
  min-width:20px;
  max-width:100%;
  min-height:20px;
  padding:2px 6px;
  line-height:16px;
  color:#f5f8fa;
  font-size:12px; }
  .bp3-tag.bp3-interactive{
    cursor:pointer; }
    .bp3-tag.bp3-interactive:hover{
      background-color:rgba(92, 112, 128, 0.85); }
    .bp3-tag.bp3-interactive.bp3-active, .bp3-tag.bp3-interactive:active{
      background-color:rgba(92, 112, 128, 0.7); }
  .bp3-tag > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag::before,
  .bp3-tag > *{
    margin-right:4px; }
  .bp3-tag:empty::before,
  .bp3-tag > :last-child{
    margin-right:0; }
  .bp3-tag:focus{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:0;
    -moz-outline-radius:6px; }
  .bp3-tag.bp3-round{
    border-radius:30px;
    padding-right:8px;
    padding-left:8px; }
  .bp3-dark .bp3-tag{
    background-color:#bfccd6;
    color:#182026; }
    .bp3-dark .bp3-tag.bp3-interactive{
      cursor:pointer; }
      .bp3-dark .bp3-tag.bp3-interactive:hover{
        background-color:rgba(191, 204, 214, 0.85); }
      .bp3-dark .bp3-tag.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-interactive:active{
        background-color:rgba(191, 204, 214, 0.7); }
    .bp3-dark .bp3-tag > .bp3-icon, .bp3-dark .bp3-tag .bp3-icon-standard, .bp3-dark .bp3-tag .bp3-icon-large{
      fill:currentColor; }
  .bp3-tag > .bp3-icon, .bp3-tag .bp3-icon-standard, .bp3-tag .bp3-icon-large{
    fill:#ffffff; }
  .bp3-tag.bp3-large,
  .bp3-large .bp3-tag{
    min-width:30px;
    min-height:30px;
    padding:0 10px;
    line-height:20px;
    font-size:14px; }
    .bp3-tag.bp3-large::before,
    .bp3-tag.bp3-large > *,
    .bp3-large .bp3-tag::before,
    .bp3-large .bp3-tag > *{
      margin-right:7px; }
    .bp3-tag.bp3-large:empty::before,
    .bp3-tag.bp3-large > :last-child,
    .bp3-large .bp3-tag:empty::before,
    .bp3-large .bp3-tag > :last-child{
      margin-right:0; }
    .bp3-tag.bp3-large.bp3-round,
    .bp3-large .bp3-tag.bp3-round{
      padding-right:12px;
      padding-left:12px; }
  .bp3-tag.bp3-intent-primary{
    background:#137cbd;
    color:#ffffff; }
    .bp3-tag.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.85); }
      .bp3-tag.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.7); }
  .bp3-tag.bp3-intent-success{
    background:#0f9960;
    color:#ffffff; }
    .bp3-tag.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.85); }
      .bp3-tag.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.7); }
  .bp3-tag.bp3-intent-warning{
    background:#d9822b;
    color:#ffffff; }
    .bp3-tag.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.85); }
      .bp3-tag.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.7); }
  .bp3-tag.bp3-intent-danger{
    background:#db3737;
    color:#ffffff; }
    .bp3-tag.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.85); }
      .bp3-tag.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.7); }
  .bp3-tag.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-tag.bp3-minimal > .bp3-icon, .bp3-tag.bp3-minimal .bp3-icon-standard, .bp3-tag.bp3-minimal .bp3-icon-large{
    fill:#5c7080; }
  .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
    background-color:rgba(138, 155, 168, 0.2);
    color:#182026; }
    .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
        background-color:rgba(92, 112, 128, 0.3); }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
        background-color:rgba(92, 112, 128, 0.4); }
    .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
      color:#f5f8fa; }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
          background-color:rgba(191, 204, 214, 0.3); }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
          background-color:rgba(191, 204, 214, 0.4); }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) > .bp3-icon, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-large{
        fill:#a7b6c2; }
  .bp3-tag.bp3-minimal.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15);
    color:#106ba3; }
    .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-primary > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-large{
      fill:#137cbd; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25);
      color:#48aff0; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
          background-color:rgba(19, 124, 189, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
          background-color:rgba(19, 124, 189, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15);
    color:#0d8050; }
    .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-success > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-large{
      fill:#0f9960; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25);
      color:#3dcc91; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
          background-color:rgba(15, 153, 96, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
          background-color:rgba(15, 153, 96, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15);
    color:#bf7326; }
    .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-warning > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-large{
      fill:#d9822b; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25);
      color:#ffb366; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
          background-color:rgba(217, 130, 43, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
          background-color:rgba(217, 130, 43, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15);
    color:#c23030; }
    .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-danger > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-large{
      fill:#db3737; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25);
      color:#ff7373; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
          background-color:rgba(219, 55, 55, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
          background-color:rgba(219, 55, 55, 0.45); }

.bp3-tag-remove{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  opacity:0.5;
  margin-top:-2px;
  margin-right:-6px !important;
  margin-bottom:-2px;
  border:none;
  background:none;
  cursor:pointer;
  padding:2px;
  padding-left:0;
  color:inherit; }
  .bp3-tag-remove:hover{
    opacity:0.8;
    background:none;
    text-decoration:none; }
  .bp3-tag-remove:active{
    opacity:1; }
  .bp3-tag-remove:empty::before{
    line-height:1;
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-weight:400;
    font-style:normal;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    content:""; }
  .bp3-large .bp3-tag-remove{
    margin-right:-10px !important;
    padding:5px;
    padding-left:0; }
    .bp3-large .bp3-tag-remove:empty::before{
      line-height:1;
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-weight:400;
      font-style:normal; }
.bp3-tag-input{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  cursor:text;
  height:auto;
  min-height:30px;
  padding-right:0;
  padding-left:5px;
  line-height:inherit; }
  .bp3-tag-input > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag-input > .bp3-tag-input-values{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag-input .bp3-tag-input-icon{
    margin-top:7px;
    margin-right:7px;
    margin-left:2px;
    color:#5c7080; }
  .bp3-tag-input .bp3-tag-input-values{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row;
    -ms-flex-wrap:wrap;
        flex-wrap:wrap;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    -ms-flex-item-align:stretch;
        align-self:stretch;
    margin-top:5px;
    margin-right:7px;
    min-width:0; }
    .bp3-tag-input .bp3-tag-input-values > *{
      -webkit-box-flex:0;
          -ms-flex-positive:0;
              flex-grow:0;
      -ms-flex-negative:0;
          flex-shrink:0; }
    .bp3-tag-input .bp3-tag-input-values > .bp3-fill{
      -webkit-box-flex:1;
          -ms-flex-positive:1;
              flex-grow:1;
      -ms-flex-negative:1;
          flex-shrink:1; }
    .bp3-tag-input .bp3-tag-input-values::before,
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-right:5px; }
    .bp3-tag-input .bp3-tag-input-values:empty::before,
    .bp3-tag-input .bp3-tag-input-values > :last-child{
      margin-right:0; }
    .bp3-tag-input .bp3-tag-input-values:first-child .bp3-input-ghost:first-child{
      padding-left:5px; }
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-bottom:5px; }
  .bp3-tag-input .bp3-tag{
    overflow-wrap:break-word; }
    .bp3-tag-input .bp3-tag.bp3-active{
      outline:rgba(19, 124, 189, 0.6) auto 2px;
      outline-offset:0;
      -moz-outline-radius:6px; }
  .bp3-tag-input .bp3-input-ghost{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:80px;
    line-height:20px; }
    .bp3-tag-input .bp3-input-ghost:disabled, .bp3-tag-input .bp3-input-ghost.bp3-disabled{
      cursor:not-allowed; }
  .bp3-tag-input .bp3-button,
  .bp3-tag-input .bp3-spinner{
    margin:3px;
    margin-left:0; }
  .bp3-tag-input .bp3-button{
    min-width:24px;
    min-height:24px;
    padding:0 7px; }
  .bp3-tag-input.bp3-large{
    height:auto;
    min-height:40px; }
    .bp3-tag-input.bp3-large::before,
    .bp3-tag-input.bp3-large > *{
      margin-right:10px; }
    .bp3-tag-input.bp3-large:empty::before,
    .bp3-tag-input.bp3-large > :last-child{
      margin-right:0; }
    .bp3-tag-input.bp3-large .bp3-tag-input-icon{
      margin-top:10px;
      margin-left:5px; }
    .bp3-tag-input.bp3-large .bp3-input-ghost{
      line-height:30px; }
    .bp3-tag-input.bp3-large .bp3-button{
      min-width:30px;
      min-height:30px;
      padding:5px 10px;
      margin:5px;
      margin-left:0; }
    .bp3-tag-input.bp3-large .bp3-spinner{
      margin:8px;
      margin-left:0; }
  .bp3-tag-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
    background-color:#ffffff; }
    .bp3-tag-input.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-tag-input .bp3-tag-input-icon, .bp3-tag-input.bp3-dark .bp3-tag-input-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-tag-input .bp3-input-ghost, .bp3-tag-input.bp3-dark .bp3-input-ghost{
    color:#f5f8fa; }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-webkit-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-moz-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost:-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::placeholder{
      color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tag-input.bp3-active, .bp3-tag-input.bp3-dark.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background-color:rgba(16, 22, 26, 0.3); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-primary, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-success, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-warning, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-danger, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-input-ghost{
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  background:none;
  padding:0; }
  .bp3-input-ghost::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost:focus{
    outline:none !important; }
.bp3-toast{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  position:relative !important;
  margin:20px 0 0;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  background-color:#ffffff;
  min-width:300px;
  max-width:500px;
  pointer-events:all; }
  .bp3-toast.bp3-toast-enter, .bp3-toast.bp3-toast-appear{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active, .bp3-toast.bp3-toast-appear-active{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-toast.bp3-toast-enter ~ .bp3-toast, .bp3-toast.bp3-toast-appear ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active ~ .bp3-toast, .bp3-toast.bp3-toast-appear-active ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-toast.bp3-toast-exit{
    opacity:1;
    -webkit-filter:blur(0);
            filter:blur(0); }
  .bp3-toast.bp3-toast-exit-active{
    opacity:0;
    -webkit-filter:blur(10px);
            filter:blur(10px);
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:opacity, filter;
    transition-property:opacity, filter, -webkit-filter;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-toast.bp3-toast-exit ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0); }
  .bp3-toast.bp3-toast-exit-active ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:50ms;
            transition-delay:50ms; }
  .bp3-toast .bp3-button-group{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    padding:5px;
    padding-left:0; }
  .bp3-toast > .bp3-icon{
    margin:12px;
    margin-right:0;
    color:#5c7080; }
  .bp3-toast.bp3-dark,
  .bp3-dark .bp3-toast{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
    background-color:#394b59; }
    .bp3-toast.bp3-dark > .bp3-icon,
    .bp3-dark .bp3-toast > .bp3-icon{
      color:#a7b6c2; }
  .bp3-toast[class*="bp3-intent-"] a{
    color:rgba(255, 255, 255, 0.7); }
    .bp3-toast[class*="bp3-intent-"] a:hover{
      color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] > .bp3-icon{
    color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button, .bp3-toast[class*="bp3-intent-"] .bp3-button::before,
  .bp3-toast[class*="bp3-intent-"] .bp3-button .bp3-icon, .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    color:rgba(255, 255, 255, 0.7) !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:focus{
    outline-color:rgba(255, 255, 255, 0.5); }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:hover{
    background-color:rgba(255, 255, 255, 0.15) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    background-color:rgba(255, 255, 255, 0.3) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button::after{
    background:rgba(255, 255, 255, 0.3) !important; }
  .bp3-toast.bp3-intent-primary{
    background-color:#137cbd;
    color:#ffffff; }
  .bp3-toast.bp3-intent-success{
    background-color:#0f9960;
    color:#ffffff; }
  .bp3-toast.bp3-intent-warning{
    background-color:#d9822b;
    color:#ffffff; }
  .bp3-toast.bp3-intent-danger{
    background-color:#db3737;
    color:#ffffff; }

.bp3-toast-message{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  padding:11px;
  word-break:break-word; }

.bp3-toast-container{
  display:-webkit-box !important;
  display:-ms-flexbox !important;
  display:flex !important;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  position:fixed;
  right:0;
  left:0;
  z-index:40;
  overflow:hidden;
  padding:0 20px 20px;
  pointer-events:none; }
  .bp3-toast-container.bp3-toast-container-top{
    top:0;
    bottom:auto; }
  .bp3-toast-container.bp3-toast-container-bottom{
    -webkit-box-orient:vertical;
    -webkit-box-direction:reverse;
        -ms-flex-direction:column-reverse;
            flex-direction:column-reverse;
    top:auto;
    bottom:0; }
  .bp3-toast-container.bp3-toast-container-left{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
  .bp3-toast-container.bp3-toast-container-right{
    -webkit-box-align:end;
        -ms-flex-align:end;
            align-items:flex-end; }

.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active) ~ .bp3-toast, .bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active) ~ .bp3-toast,
.bp3-toast-container-bottom .bp3-toast.bp3-toast-leave-active ~ .bp3-toast{
  -webkit-transform:translateY(60px);
          transform:translateY(60px); }
.bp3-tooltip{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1); }
  .bp3-tooltip .bp3-popover-arrow{
    position:absolute;
    width:22px;
    height:22px; }
    .bp3-tooltip .bp3-popover-arrow::before{
      margin:4px;
      width:14px;
      height:14px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip{
    margin-top:-11px;
    margin-bottom:11px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
      bottom:-8px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip{
    margin-left:11px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
      left:-8px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip{
    margin-top:11px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
      top:-8px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip{
    margin-right:11px;
    margin-left:-11px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
      right:-8px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-tooltip > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-tooltip > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
    top:-0.22183px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
    right:-0.22183px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
    left:-0.22183px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
    bottom:-0.22183px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-tooltip .bp3-popover-content{
    background:#394b59;
    color:#f5f8fa; }
  .bp3-tooltip .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-tooltip .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-tooltip .bp3-popover-arrow-fill{
    fill:#394b59; }
  .bp3-popover-enter > .bp3-tooltip, .bp3-popover-appear > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8); }
  .bp3-popover-enter-active > .bp3-tooltip, .bp3-popover-appear-active > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-popover-exit > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-tooltip .bp3-popover-content{
    padding:10px 12px; }
  .bp3-tooltip.bp3-dark,
  .bp3-dark .bp3-tooltip{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-tooltip .bp3-popover-content{
      background:#e1e8ed;
      color:#394b59; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-fill{
      fill:#e1e8ed; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-content{
    background:#137cbd;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-arrow-fill{
    fill:#137cbd; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-content{
    background:#0f9960;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-arrow-fill{
    fill:#0f9960; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-content{
    background:#d9822b;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-arrow-fill{
    fill:#d9822b; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-content{
    background:#db3737;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-arrow-fill{
    fill:#db3737; }

.bp3-tooltip-indicator{
  border-bottom:dotted 1px;
  cursor:help; }
.bp3-tree .bp3-icon, .bp3-tree .bp3-icon-standard, .bp3-tree .bp3-icon-large{
  color:#5c7080; }
  .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-tree .bp3-icon.bp3-intent-success, .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-tree-node-list{
  margin:0;
  padding-left:0;
  list-style:none; }

.bp3-tree-root{
  position:relative;
  background-color:transparent;
  cursor:default;
  padding-left:0; }

.bp3-tree-node-content-0{
  padding-left:0px; }

.bp3-tree-node-content-1{
  padding-left:23px; }

.bp3-tree-node-content-2{
  padding-left:46px; }

.bp3-tree-node-content-3{
  padding-left:69px; }

.bp3-tree-node-content-4{
  padding-left:92px; }

.bp3-tree-node-content-5{
  padding-left:115px; }

.bp3-tree-node-content-6{
  padding-left:138px; }

.bp3-tree-node-content-7{
  padding-left:161px; }

.bp3-tree-node-content-8{
  padding-left:184px; }

.bp3-tree-node-content-9{
  padding-left:207px; }

.bp3-tree-node-content-10{
  padding-left:230px; }

.bp3-tree-node-content-11{
  padding-left:253px; }

.bp3-tree-node-content-12{
  padding-left:276px; }

.bp3-tree-node-content-13{
  padding-left:299px; }

.bp3-tree-node-content-14{
  padding-left:322px; }

.bp3-tree-node-content-15{
  padding-left:345px; }

.bp3-tree-node-content-16{
  padding-left:368px; }

.bp3-tree-node-content-17{
  padding-left:391px; }

.bp3-tree-node-content-18{
  padding-left:414px; }

.bp3-tree-node-content-19{
  padding-left:437px; }

.bp3-tree-node-content-20{
  padding-left:460px; }

.bp3-tree-node-content{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  width:100%;
  height:30px;
  padding-right:5px; }
  .bp3-tree-node-content:hover{
    background-color:rgba(191, 204, 214, 0.4); }

.bp3-tree-node-caret,
.bp3-tree-node-caret-none{
  min-width:30px; }

.bp3-tree-node-caret{
  color:#5c7080;
  -webkit-transform:rotate(0deg);
          transform:rotate(0deg);
  cursor:pointer;
  padding:7px;
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tree-node-caret:hover{
    color:#182026; }
  .bp3-dark .bp3-tree-node-caret{
    color:#a7b6c2; }
    .bp3-dark .bp3-tree-node-caret:hover{
      color:#f5f8fa; }
  .bp3-tree-node-caret.bp3-tree-node-caret-open{
    -webkit-transform:rotate(90deg);
            transform:rotate(90deg); }
  .bp3-tree-node-caret.bp3-icon-standard::before{
    content:""; }

.bp3-tree-node-icon{
  position:relative;
  margin-right:7px; }

.bp3-tree-node-label{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  position:relative;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-label span{
    display:inline; }

.bp3-tree-node-secondary-label{
  padding:0 5px;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-secondary-label .bp3-popover-wrapper,
  .bp3-tree-node-secondary-label .bp3-popover-target{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-content{
  background-color:inherit;
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-tree-node.bp3-disabled .bp3-tree-node-caret,
.bp3-tree-node.bp3-disabled .bp3-tree-node-icon{
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content,
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-standard, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-large{
    color:#ffffff; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret::before{
    color:rgba(255, 255, 255, 0.7); }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret:hover::before{
    color:#ffffff; }

.bp3-dark .bp3-tree-node-content:hover{
  background-color:rgba(92, 112, 128, 0.3); }

.bp3-dark .bp3-tree .bp3-icon, .bp3-dark .bp3-tree .bp3-icon-standard, .bp3-dark .bp3-tree .bp3-icon-large{
  color:#a7b6c2; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-dark .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
/*!

Copyright 2017-present Palantir Technologies, Inc. All rights reserved.
Licensed under the Apache License, Version 2.0.

*/
.bp3-omnibar{
  -webkit-filter:blur(0);
          filter:blur(0);
  opacity:1;
  top:20vh;
  left:calc(50% - 250px);
  z-index:21;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  background-color:#ffffff;
  width:500px; }
  .bp3-omnibar.bp3-overlay-enter, .bp3-omnibar.bp3-overlay-appear{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2; }
  .bp3-omnibar.bp3-overlay-enter-active, .bp3-omnibar.bp3-overlay-appear-active{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-omnibar.bp3-overlay-exit{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1; }
  .bp3-omnibar.bp3-overlay-exit-active{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-omnibar .bp3-input{
    border-radius:0;
    background-color:transparent; }
    .bp3-omnibar .bp3-input, .bp3-omnibar .bp3-input:focus{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-omnibar .bp3-menu{
    border-radius:0;
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
    background-color:transparent;
    max-height:calc(60vh - 40px);
    overflow:auto; }
    .bp3-omnibar .bp3-menu:empty{
      display:none; }
  .bp3-dark .bp3-omnibar, .bp3-omnibar.bp3-dark{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    background-color:#30404d; }

.bp3-omnibar-overlay .bp3-overlay-backdrop{
  background-color:rgba(16, 22, 26, 0.2); }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-width:400px;
  max-height:300px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }

.bp3-multi-select{
  min-width:150px; }

.bp3-multi-select-popover .bp3-menu{
  max-width:400px;
  max-height:300px;
  overflow:auto; }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-width:400px;
  max-height:300px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDhoLTIuODFjLS40NS0uNzgtMS4wNy0xLjQ1LTEuODItMS45NkwxNyA0LjQxIDE1LjU5IDNsLTIuMTcgMi4xN0MxMi45NiA1LjA2IDEyLjQ5IDUgMTIgNWMtLjQ5IDAtLjk2LjA2LTEuNDEuMTdMOC40MSAzIDcgNC40MWwxLjYyIDEuNjNDNy44OCA2LjU1IDcuMjYgNy4yMiA2LjgxIDhINHYyaDIuMDljLS4wNS4zMy0uMDkuNjYtLjA5IDF2MUg0djJoMnYxYzAgLjM0LjA0LjY3LjA5IDFINHYyaDIuODFjMS4wNCAxLjc5IDIuOTcgMyA1LjE5IDNzNC4xNS0xLjIxIDUuMTktM0gyMHYtMmgtMi4wOWMuMDUtLjMzLjA5LS42Ni4wOS0xdi0xaDJ2LTJoLTJ2LTFjMC0uMzQtLjA0LS42Ny0uMDktMUgyMFY4em0tNiA4aC00di0yaDR2MnptMC00aC00di0yaDR2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTYuMTdMNC44MyAxMmwtMS40MiAxLjQxTDkgMTkgMjEgN2wtMS40MS0xLjQxeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1pY29uLWJyYW5kMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNmZmYiPgogICAgPHBhdGggZD0iTTEwNSAxMjcuM2g0MHYxMi44aC00MHpNNTEuMSA3N0w3NCA5OS45bC0yMy4zIDIzLjMgMTAuNSAxMC41IDIzLjMtMjMuM0w5NSA5OS45IDg0LjUgODkuNCA2MS42IDY2LjV6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNGOUE4MjUiPgogICAgPHBhdGggZD0iTTIwLjIgMTEuOGMtMS42IDAtMS43LjUtMS43IDEgMCAuNC4xLjkuMSAxLjMuMS41LjEuOS4xIDEuMyAwIDEuNy0xLjQgMi4zLTMuNSAyLjNoLS45di0xLjloLjVjMS4xIDAgMS40IDAgMS40LS44IDAtLjMgMC0uNi0uMS0xIDAtLjQtLjEtLjgtLjEtMS4yIDAtMS4zIDAtMS44IDEuMy0yLTEuMy0uMi0xLjMtLjctMS4zLTIgMC0uNC4xLS44LjEtMS4yLjEtLjQuMS0uNy4xLTEgMC0uOC0uNC0uNy0xLjQtLjhoLS41VjQuMWguOWMyLjIgMCAzLjUuNyAzLjUgMi4zIDAgLjQtLjEuOS0uMSAxLjMtLjEuNS0uMS45LS4xIDEuMyAwIC41LjIgMSAxLjcgMXYxLjh6TTEuOCAxMC4xYzEuNiAwIDEuNy0uNSAxLjctMSAwLS40LS4xLS45LS4xLTEuMy0uMS0uNS0uMS0uOS0uMS0xLjMgMC0xLjYgMS40LTIuMyAzLjUtMi4zaC45djEuOWgtLjVjLTEgMC0xLjQgMC0xLjQuOCAwIC4zIDAgLjYuMSAxIDAgLjIuMS42LjEgMSAwIDEuMyAwIDEuOC0xLjMgMkM2IDExLjIgNiAxMS43IDYgMTNjMCAuNC0uMS44LS4xIDEuMi0uMS4zLS4xLjctLjEgMSAwIC44LjMuOCAxLjQuOGguNXYxLjloLS45Yy0yLjEgMC0zLjUtLjYtMy41LTIuMyAwLS40LjEtLjkuMS0xLjMuMS0uNS4xLS45LjEtMS4zIDAtLjUtLjItMS0xLjctMXYtMS45eiIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSIxMy44IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY3g9IjExIiBjeT0iOC4yIiByPSIyLjEiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgPGcgY2xhc3M9ImpwLWljb24td2FybjAiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4=);
  --jp-icon-listings-info: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPHN2ZyB2ZXJzaW9uPSIxLjEiIGlkPSJDYXBhXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSIwIDAgNTAuOTc4IDUwLjk3OCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNTAuOTc4IDUwLjk3ODsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPGc+DQoJPGc+DQoJCTxnPg0KCQkJPHBhdGggc3R5bGU9ImZpbGw6IzAxMDAwMjsiIGQ9Ik00My41Miw3LjQ1OEMzOC43MTEsMi42NDgsMzIuMzA3LDAsMjUuNDg5LDBDMTguNjcsMCwxMi4yNjYsMi42NDgsNy40NTgsNy40NTgNCgkJCQljLTkuOTQzLDkuOTQxLTkuOTQzLDI2LjExOSwwLDM2LjA2MmM0LjgwOSw0LjgwOSwxMS4yMTIsNy40NTYsMTguMDMxLDcuNDU4YzAsMCwwLjAwMSwwLDAuMDAyLDANCgkJCQljNi44MTYsMCwxMy4yMjEtMi42NDgsMTguMDI5LTcuNDU4YzQuODA5LTQuODA5LDcuNDU3LTExLjIxMiw3LjQ1Ny0xOC4wM0M1MC45NzcsMTguNjcsNDguMzI4LDEyLjI2Niw0My41Miw3LjQ1OHoNCgkJCQkgTTQyLjEwNiw0Mi4xMDVjLTQuNDMyLDQuNDMxLTEwLjMzMiw2Ljg3Mi0xNi42MTUsNi44NzJoLTAuMDAyYy02LjI4NS0wLjAwMS0xMi4xODctMi40NDEtMTYuNjE3LTYuODcyDQoJCQkJYy05LjE2Mi05LjE2My05LjE2Mi0yNC4wNzEsMC0zMy4yMzNDMTMuMzAzLDQuNDQsMTkuMjA0LDIsMjUuNDg5LDJjNi4yODQsMCwxMi4xODYsMi40NCwxNi42MTcsNi44NzINCgkJCQljNC40MzEsNC40MzEsNi44NzEsMTAuMzMyLDYuODcxLDE2LjYxN0M0OC45NzcsMzEuNzcyLDQ2LjUzNiwzNy42NzUsNDIuMTA2LDQyLjEwNXoiLz4NCgkJPC9nPg0KCQk8Zz4NCgkJCTxwYXRoIHN0eWxlPSJmaWxsOiMwMTAwMDI7IiBkPSJNMjMuNTc4LDMyLjIxOGMtMC4wMjMtMS43MzQsMC4xNDMtMy4wNTksMC40OTYtMy45NzJjMC4zNTMtMC45MTMsMS4xMS0xLjk5NywyLjI3Mi0zLjI1Mw0KCQkJCWMwLjQ2OC0wLjUzNiwwLjkyMy0xLjA2MiwxLjM2Ny0xLjU3NWMwLjYyNi0wLjc1MywxLjEwNC0xLjQ3OCwxLjQzNi0yLjE3NWMwLjMzMS0wLjcwNywwLjQ5NS0xLjU0MSwwLjQ5NS0yLjUNCgkJCQljMC0xLjA5Ni0wLjI2LTIuMDg4LTAuNzc5LTIuOTc5Yy0wLjU2NS0wLjg3OS0xLjUwMS0xLjMzNi0yLjgwNi0xLjM2OWMtMS44MDIsMC4wNTctMi45ODUsMC42NjctMy41NSwxLjgzMg0KCQkJCWMtMC4zMDEsMC41MzUtMC41MDMsMS4xNDEtMC42MDcsMS44MTRjLTAuMTM5LDAuNzA3LTAuMjA3LDEuNDMyLTAuMjA3LDIuMTc0aC0yLjkzN2MtMC4wOTEtMi4yMDgsMC40MDctNC4xMTQsMS40OTMtNS43MTkNCgkJCQljMS4wNjItMS42NCwyLjg1NS0yLjQ4MSw1LjM3OC0yLjUyN2MyLjE2LDAuMDIzLDMuODc0LDAuNjA4LDUuMTQxLDEuNzU4YzEuMjc4LDEuMTYsMS45MjksMi43NjQsMS45NSw0LjgxMQ0KCQkJCWMwLDEuMTQyLTAuMTM3LDIuMTExLTAuNDEsMi45MTFjLTAuMzA5LDAuODQ1LTAuNzMxLDEuNTkzLTEuMjY4LDIuMjQzYy0wLjQ5MiwwLjY1LTEuMDY4LDEuMzE4LTEuNzMsMi4wMDINCgkJCQljLTAuNjUsMC42OTctMS4zMTMsMS40NzktMS45ODcsMi4zNDZjLTAuMjM5LDAuMzc3LTAuNDI5LDAuNzc3LTAuNTY1LDEuMTk5Yy0wLjE2LDAuOTU5LTAuMjE3LDEuOTUxLTAuMTcxLDIuOTc5DQoJCQkJQzI2LjU4OSwzMi4yMTgsMjMuNTc4LDMyLjIxOCwyMy41NzgsMzIuMjE4eiBNMjMuNTc4LDM4LjIydi0zLjQ4NGgzLjA3NnYzLjQ4NEgyMy41Nzh6Ii8+DQoJCTwvZz4NCgk8L2c+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8L3N2Zz4NCg==);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMEQ0N0ExIj4KICAgIDxwYXRoIGQ9Ik0xMS4xIDYuOVY1LjhINi45YzAtLjUgMC0xLjMuMi0xLjYuNC0uNy44LTEuMSAxLjctMS40IDEuNy0uMyAyLjUtLjMgMy45LS4xIDEgLjEgMS45LjkgMS45IDEuOXY0LjJjMCAuNS0uOSAxLjYtMiAxLjZIOC44Yy0xLjUgMC0yLjQgMS40LTIuNCAyLjh2Mi4ySDQuN0MzLjUgMTUuMSAzIDE0IDMgMTMuMVY5Yy0uMS0xIC42LTIgMS44LTIgMS41LS4xIDYuMy0uMSA2LjMtLjF6Ii8+CiAgICA8cGF0aCBkPSJNMTAuOSAxNS4xdjEuMWg0LjJjMCAuNSAwIDEuMy0uMiAxLjYtLjQuNy0uOCAxLjEtMS43IDEuNC0xLjcuMy0yLjUuMy0zLjkuMS0xLS4xLTEuOS0uOS0xLjktMS45di00LjJjMC0uNS45LTEuNiAyLTEuNmgzLjhjMS41IDAgMi40LTEuNCAyLjQtMi44VjYuNmgxLjdDMTguNSA2LjkgMTkgOCAxOSA4LjlWMTNjMCAxLS43IDIuMS0xLjkgMi4xaC02LjJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMikiIGZpbGw9IiMzMzMzMzMiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uLWFjY2VudDIganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGQ9Ik01LjA1NjY0IDguNzYxNzJDNS4wNTY2NCA4LjU5NzY2IDUuMDMxMjUgOC40NTMxMiA0Ljk4MDQ3IDguMzI4MTJDNC45MzM1OSA4LjE5OTIyIDQuODU1NDcgOC4wODIwMyA0Ljc0NjA5IDcuOTc2NTZDNC42NDA2MiA3Ljg3MTA5IDQuNSA3Ljc3NTM5IDQuMzI0MjIgNy42ODk0NUM0LjE1MjM0IDcuNTk5NjEgMy45NDMzNiA3LjUxMTcyIDMuNjk3MjcgNy40MjU3OEMzLjMwMjczIDcuMjg1MTYgMi45NDMzNiA3LjEzNjcyIDIuNjE5MTQgNi45ODA0N0MyLjI5NDkyIDYuODI0MjIgMi4wMTc1OCA2LjY0MjU4IDEuNzg3MTEgNi40MzU1NUMxLjU2MDU1IDYuMjI4NTIgMS4zODQ3NyA1Ljk4ODI4IDEuMjU5NzcgNS43MTQ4NEMxLjEzNDc3IDUuNDM3NSAxLjA3MjI3IDUuMTA5MzggMS4wNzIyNyA0LjczMDQ3QzEuMDcyMjcgNC4zOTg0NCAxLjEyODkxIDQuMDk1NyAxLjI0MjE5IDMuODIyMjdDMS4zNTU0NyAzLjU0NDkyIDEuNTE1NjIgMy4zMDQ2OSAxLjcyMjY2IDMuMTAxNTZDMS45Mjk2OSAyLjg5ODQ0IDIuMTc5NjkgMi43MzQzNyAyLjQ3MjY2IDIuNjA5MzhDMi43NjU2MiAyLjQ4NDM4IDMuMDkxOCAyLjQwNDMgMy40NTExNyAyLjM2OTE0VjEuMTA5MzhINC4zODg2N1YyLjM4MDg2QzQuNzQwMjMgMi40Mjc3MyA1LjA1NjY0IDIuNTIzNDQgNS4zMzc4OSAyLjY2Nzk3QzUuNjE5MTQgMi44MTI1IDUuODU3NDIgMy4wMDE5NSA2LjA1MjczIDMuMjM2MzNDNi4yNTE5NSAzLjQ2NjggNi40MDQzIDMuNzQwMjMgNi41MDk3NyA0LjA1NjY0QzYuNjE5MTQgNC4zNjkxNCA2LjY3MzgzIDQuNzIwNyA2LjY3MzgzIDUuMTExMzNINS4wNDQ5MkM1LjA0NDkyIDQuNjM4NjcgNC45Mzc1IDQuMjgxMjUgNC43MjI2NiA0LjAzOTA2QzQuNTA3ODEgMy43OTI5NyA0LjIxNjggMy42Njk5MiAzLjg0OTYxIDMuNjY5OTJDMy42NTAzOSAzLjY2OTkyIDMuNDc2NTYgMy42OTcyNyAzLjMyODEyIDMuNzUxOTVDMy4xODM1OSAzLjgwMjczIDMuMDY0NDUgMy44NzY5NSAyLjk3MDcgMy45NzQ2MUMyLjg3Njk1IDQuMDY4MzYgMi44MDY2NCA0LjE3OTY5IDIuNzU5NzcgNC4zMDg1OUMyLjcxNjggNC40Mzc1IDIuNjk1MzEgNC41NzgxMiAyLjY5NTMxIDQuNzMwNDdDMi42OTUzMSA0Ljg4MjgxIDIuNzE2OCA1LjAxOTUzIDIuNzU5NzcgNS4xNDA2MkMyLjgwNjY0IDUuMjU3ODEgMi44ODI4MSA1LjM2NzE5IDIuOTg4MjggNS40Njg3NUMzLjA5NzY2IDUuNTcwMzEgMy4yNDAyMyA1LjY2Nzk3IDMuNDE2MDIgNS43NjE3MkMzLjU5MTggNS44NTE1NiAzLjgxMDU1IDUuOTQzMzYgNC4wNzIyNyA2LjAzNzExQzQuNDY2OCA2LjE4NTU1IDQuODI0MjIgNi4zMzk4NCA1LjE0NDUzIDYuNUM1LjQ2NDg0IDYuNjU2MjUgNS43MzgyOCA2LjgzOTg0IDUuOTY0ODQgNy4wNTA3OEM2LjE5NTMxIDcuMjU3ODEgNi4zNzEwOSA3LjUgNi40OTIxOSA3Ljc3NzM0QzYuNjE3MTkgOC4wNTA3OCA2LjY3OTY5IDguMzc1IDYuNjc5NjkgOC43NUM2LjY3OTY5IDkuMDkzNzUgNi42MjMwNSA5LjQwNDMgNi41MDk3NyA5LjY4MTY0QzYuMzk2NDggOS45NTUwOCA2LjIzNDM4IDEwLjE5MTQgNi4wMjM0NCAxMC4zOTA2QzUuODEyNSAxMC41ODk4IDUuNTU4NTkgMTAuNzUgNS4yNjE3MiAxMC44NzExQzQuOTY0ODQgMTAuOTg4MyA0LjYzMjgxIDExLjA2NDUgNC4yNjU2MiAxMS4wOTk2VjEyLjI0OEgzLjMzMzk4VjExLjA5OTZDMy4wMDE5NSAxMS4wNjg0IDIuNjc5NjkgMTAuOTk2MSAyLjM2NzE5IDEwLjg4MjhDMi4wNTQ2OSAxMC43NjU2IDEuNzc3MzQgMTAuNTk3NyAxLjUzNTE2IDEwLjM3ODlDMS4yOTY4OCAxMC4xNjAyIDEuMTA1NDcgOS44ODQ3NyAwLjk2MDkzOCA5LjU1MjczQzAuODE2NDA2IDkuMjE2OCAwLjc0NDE0MSA4LjgxNDQ1IDAuNzQ0MTQxIDguMzQ1N0gyLjM3ODkxQzIuMzc4OTEgOC42MjY5NSAyLjQxOTkyIDguODYzMjggMi41MDE5NSA5LjA1NDY5QzIuNTgzOTggOS4yNDIxOSAyLjY4OTQ1IDkuMzkyNTggMi44MTgzNiA5LjUwNTg2QzIuOTUxMTcgOS42MTUyMyAzLjEwMTU2IDkuNjkzMzYgMy4yNjk1MyA5Ljc0MDIzQzMuNDM3NSA5Ljc4NzExIDMuNjA5MzggOS44MTA1NSAzLjc4NTE2IDkuODEwNTVDNC4yMDMxMiA5LjgxMDU1IDQuNTE5NTMgOS43MTI4OSA0LjczNDM4IDkuNTE3NThDNC45NDkyMiA5LjMyMjI3IDUuMDU2NjQgOS4wNzAzMSA1LjA1NjY0IDguNzYxNzJaTTEzLjQxOCAxMi4yNzE1SDguMDc0MjJWMTFIMTMuNDE4VjEyLjI3MTVaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzLjk1MjY0IDYpIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4K);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTUgMTVIM3YyaDEydi0yem0wLThIM3YyaDEyVjd6TTMgMTNoMTh2LTJIM3Yyem0wIDhoMTh2LTJIM3Yyek0zIDN2MmgxOFYzSDN6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}
.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}
.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}
.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}
.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}
.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}
.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}
.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}
.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}
.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}
.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}
.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}
.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}
.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}
.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}
.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}
.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}
.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}
.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}
.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}
.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}
.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}
.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}
.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}
.jp-FileIcon {
  background-image: var(--jp-icon-file);
}
.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}
.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}
.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}
.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}
.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}
.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}
.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}
.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}
.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}
.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}
.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}
.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}
.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}
.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}
.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}
.jp-ListIcon {
  background-image: var(--jp-icon-list);
}
.jp-ListingsInfoIcon {
  background-image: var(--jp-icon-listings-info);
}
.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}
.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}
.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}
.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}
.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}
.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}
.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}
.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}
.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}
.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}
.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}
.jp-RunIcon {
  background-image: var(--jp-icon-run);
}
.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}
.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}
.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}
.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}
.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}
.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}
.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}
.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}
.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}
.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}
.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}
.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}
.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

:root {
  --jp-icon-search-white: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
}

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}
/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}
/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}
/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}
.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}
.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}
.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}
.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}
.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}
.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}
.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}
.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}
/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}
.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}
.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}
.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}
.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}
.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}
.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}
/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

/* CSS for icons in selected items in the settings editor */
#setting-editor .jp-PluginList .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
#setting-editor
  .jp-PluginList
  .jp-mod-selected
  .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected tabs in the sidebar tab manager */
#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable[fill] {
  fill: #fff;
}

#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable[fill] {
  fill: var(--jp-brand-color1);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable-inverse[fill] {
  fill: #fff;
}

/**
 * TODO: come up with non css-hack solution for showing the busy icon on top
 *  of the close icon
 * CSS for complex behavior of close icon of tabs in the sidebar tab manager
 */
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-dirty.jp-mod-active
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: #fff;
}

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) svg {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

/* Override Blueprint's _reset.scss styles */
html {
  box-sizing: unset;
}

*,
*::before,
*::after {
  box-sizing: unset;
}

body {
  color: unset;
  font-family: var(--jp-ui-font-family);
}

p {
  margin-top: unset;
  margin-bottom: unset;
}

small {
  font-size: unset;
}

strong {
  font-weight: unset;
}

/* Override Blueprint's _typography.scss styles */
a {
  text-decoration: unset;
  color: unset;
}
a:hover {
  text-decoration: unset;
  color: unset;
}

/* Override Blueprint's _accessibility.scss styles */
:focus {
  outline: unset;
  outline-offset: unset;
  -moz-outline-radius: unset;
}

/* Styles for ui-components */
.jp-Button {
  border-radius: var(--jp-border-radius);
  padding: 0px 12px;
  font-size: var(--jp-ui-font-size1);
}

/* Use our own theme for hover styles */
button.jp-Button.bp3-button.bp3-minimal:hover {
  background-color: var(--jp-layout-color2);
}
.jp-Button.minimal {
  color: unset !important;
}

.jp-Button.jp-ToolbarButtonComponent {
  text-transform: none;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color3);
}

.jp-BPIcon {
  display: inline-block;
  vertical-align: middle;
  margin: auto;
}

/* Stop blueprint futzing with our icon fills */
.bp3-icon.jp-BPIcon > svg:not([fill]) {
  fill: var(--jp-inverse-layout-color3);
}

.jp-InputGroupAction {
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

/* Use our own theme for hover and option styles */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}
select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-top: 1px solid var(--jp-border-color2);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-Collapse-header {
  padding: 1px 12px;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size2);
}

.jp-Collapse-header:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Collapse-contents {
  padding: 0px 12px 0px 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0px;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0px 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.lm-CommandPalette-wrapper::after {
  content: ' ';
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  height: 30px;
  width: 10px;
  padding: 0px 10px;
  background-image: var(--jp-icon-search-white);
  background-size: 20px;
  background-repeat: no-repeat;
  background-position: center;
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color3);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0px;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color3);
}

.lm-CommandPalette-item.lm-mod-active {
  background: var(--jp-layout-color3);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  background: var(--jp-layout-color4);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color3);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.4;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty:after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0px 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0px;
  left: 0px;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px;
  padding-bottom: 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0px;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

.jp-Dialog-header {
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0px 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

.jp-HoverBox.jp-mod-outofview {
  display: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;

  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;

  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #aa00ff;

  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;

  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;

  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;

  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;

  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;

  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;

  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;

  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;

  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;

  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ffff00;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;

  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;

  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;

  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;

  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;

  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eeeeee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;

  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent:before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent:after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0px 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  height: 28px;
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  background-color: var(--jp-layout-color1);
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0px 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  height: 32px;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 1;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px;
  margin: 0px;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px 6px;
  margin: 0px;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent span {
  padding: 0px;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ body.p-mod-override-cursor *, /* </DEPRECATED> */
body.lm-mod-override-cursor * {
  cursor: inherit !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* BASICS */

.CodeMirror {
  /* Set height, width, borders, and global font properties here */
  font-family: monospace;
  height: 300px;
  color: black;
  direction: ltr;
}

/* PADDING */

.CodeMirror-lines {
  padding: 4px 0; /* Vertical padding around content */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  padding: 0 4px; /* Horizontal padding of content */
}

.CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  background-color: white; /* The little square between H and V scrollbars */
}

/* GUTTER */

.CodeMirror-gutters {
  border-right: 1px solid #ddd;
  background-color: #f7f7f7;
  white-space: nowrap;
}
.CodeMirror-linenumbers {}
.CodeMirror-linenumber {
  padding: 0 3px 0 5px;
  min-width: 20px;
  text-align: right;
  color: #999;
  white-space: nowrap;
}

.CodeMirror-guttermarker { color: black; }
.CodeMirror-guttermarker-subtle { color: #999; }

/* CURSOR */

.CodeMirror-cursor {
  border-left: 1px solid black;
  border-right: none;
  width: 0;
}
/* Shown when moving in bi-directional text */
.CodeMirror div.CodeMirror-secondarycursor {
  border-left: 1px solid silver;
}
.cm-fat-cursor .CodeMirror-cursor {
  width: auto;
  border: 0 !important;
  background: #7e7;
}
.cm-fat-cursor div.CodeMirror-cursors {
  z-index: 1;
}
.cm-fat-cursor-mark {
  background-color: rgba(20, 255, 20, 0.5);
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
}
.cm-animate-fat-cursor {
  width: auto;
  border: 0;
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
  background-color: #7e7;
}
@-moz-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@-webkit-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}

/* Can style cursor different in overwrite (non-insert) mode */
.CodeMirror-overwrite .CodeMirror-cursor {}

.cm-tab { display: inline-block; text-decoration: inherit; }

.CodeMirror-rulers {
  position: absolute;
  left: 0; right: 0; top: -50px; bottom: 0;
  overflow: hidden;
}
.CodeMirror-ruler {
  border-left: 1px solid #ccc;
  top: 0; bottom: 0;
  position: absolute;
}

/* DEFAULT THEME */

.cm-s-default .cm-header {color: blue;}
.cm-s-default .cm-quote {color: #090;}
.cm-negative {color: #d44;}
.cm-positive {color: #292;}
.cm-header, .cm-strong {font-weight: bold;}
.cm-em {font-style: italic;}
.cm-link {text-decoration: underline;}
.cm-strikethrough {text-decoration: line-through;}

.cm-s-default .cm-keyword {color: #708;}
.cm-s-default .cm-atom {color: #219;}
.cm-s-default .cm-number {color: #164;}
.cm-s-default .cm-def {color: #00f;}
.cm-s-default .cm-variable,
.cm-s-default .cm-punctuation,
.cm-s-default .cm-property,
.cm-s-default .cm-operator {}
.cm-s-default .cm-variable-2 {color: #05a;}
.cm-s-default .cm-variable-3, .cm-s-default .cm-type {color: #085;}
.cm-s-default .cm-comment {color: #a50;}
.cm-s-default .cm-string {color: #a11;}
.cm-s-default .cm-string-2 {color: #f50;}
.cm-s-default .cm-meta {color: #555;}
.cm-s-default .cm-qualifier {color: #555;}
.cm-s-default .cm-builtin {color: #30a;}
.cm-s-default .cm-bracket {color: #997;}
.cm-s-default .cm-tag {color: #170;}
.cm-s-default .cm-attribute {color: #00c;}
.cm-s-default .cm-hr {color: #999;}
.cm-s-default .cm-link {color: #00c;}

.cm-s-default .cm-error {color: #f00;}
.cm-invalidchar {color: #f00;}

.CodeMirror-composing { border-bottom: 2px solid; }

/* Default styles for common addons */

div.CodeMirror span.CodeMirror-matchingbracket {color: #0b0;}
div.CodeMirror span.CodeMirror-nonmatchingbracket {color: #a22;}
.CodeMirror-matchingtag { background: rgba(255, 150, 0, .3); }
.CodeMirror-activeline-background {background: #e8f2ff;}

/* STOP */

/* The rest of this file contains styles related to the mechanics of
   the editor. You probably shouldn't touch them. */

.CodeMirror {
  position: relative;
  overflow: hidden;
  background: white;
}

.CodeMirror-scroll {
  overflow: scroll !important; /* Things will break if this is overridden */
  /* 30px is the magic margin used to hide the element's real scrollbars */
  /* See overflow: hidden in .CodeMirror */
  margin-bottom: -30px; margin-right: -30px;
  padding-bottom: 30px;
  height: 100%;
  outline: none; /* Prevent dragging from highlighting the element */
  position: relative;
}
.CodeMirror-sizer {
  position: relative;
  border-right: 30px solid transparent;
}

/* The fake, visible scrollbars. Used to force redraw during scrolling
   before actual scrolling happens, thus preventing shaking and
   flickering artifacts. */
.CodeMirror-vscrollbar, .CodeMirror-hscrollbar, .CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  position: absolute;
  z-index: 6;
  display: none;
}
.CodeMirror-vscrollbar {
  right: 0; top: 0;
  overflow-x: hidden;
  overflow-y: scroll;
}
.CodeMirror-hscrollbar {
  bottom: 0; left: 0;
  overflow-y: hidden;
  overflow-x: scroll;
}
.CodeMirror-scrollbar-filler {
  right: 0; bottom: 0;
}
.CodeMirror-gutter-filler {
  left: 0; bottom: 0;
}

.CodeMirror-gutters {
  position: absolute; left: 0; top: 0;
  min-height: 100%;
  z-index: 3;
}
.CodeMirror-gutter {
  white-space: normal;
  height: 100%;
  display: inline-block;
  vertical-align: top;
  margin-bottom: -30px;
}
.CodeMirror-gutter-wrapper {
  position: absolute;
  z-index: 4;
  background: none !important;
  border: none !important;
}
.CodeMirror-gutter-background {
  position: absolute;
  top: 0; bottom: 0;
  z-index: 4;
}
.CodeMirror-gutter-elt {
  position: absolute;
  cursor: default;
  z-index: 4;
}
.CodeMirror-gutter-wrapper ::selection { background-color: transparent }
.CodeMirror-gutter-wrapper ::-moz-selection { background-color: transparent }

.CodeMirror-lines {
  cursor: text;
  min-height: 1px; /* prevents collapsing before first draw */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  /* Reset some styles that the rest of the page might have set */
  -moz-border-radius: 0; -webkit-border-radius: 0; border-radius: 0;
  border-width: 0;
  background: transparent;
  font-family: inherit;
  font-size: inherit;
  margin: 0;
  white-space: pre;
  word-wrap: normal;
  line-height: inherit;
  color: inherit;
  z-index: 2;
  position: relative;
  overflow: visible;
  -webkit-tap-highlight-color: transparent;
  -webkit-font-variant-ligatures: contextual;
  font-variant-ligatures: contextual;
}
.CodeMirror-wrap pre.CodeMirror-line,
.CodeMirror-wrap pre.CodeMirror-line-like {
  word-wrap: break-word;
  white-space: pre-wrap;
  word-break: normal;
}

.CodeMirror-linebackground {
  position: absolute;
  left: 0; right: 0; top: 0; bottom: 0;
  z-index: 0;
}

.CodeMirror-linewidget {
  position: relative;
  z-index: 2;
  padding: 0.1px; /* Force widget margins to stay inside of the container */
}

.CodeMirror-widget {}

.CodeMirror-rtl pre { direction: rtl; }

.CodeMirror-code {
  outline: none;
}

/* Force content-box sizing for the elements where we expect it */
.CodeMirror-scroll,
.CodeMirror-sizer,
.CodeMirror-gutter,
.CodeMirror-gutters,
.CodeMirror-linenumber {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

.CodeMirror-measure {
  position: absolute;
  width: 100%;
  height: 0;
  overflow: hidden;
  visibility: hidden;
}

.CodeMirror-cursor {
  position: absolute;
  pointer-events: none;
}
.CodeMirror-measure pre { position: static; }

div.CodeMirror-cursors {
  visibility: hidden;
  position: relative;
  z-index: 3;
}
div.CodeMirror-dragcursors {
  visibility: visible;
}

.CodeMirror-focused div.CodeMirror-cursors {
  visibility: visible;
}

.CodeMirror-selected { background: #d9d9d9; }
.CodeMirror-focused .CodeMirror-selected { background: #d7d4f0; }
.CodeMirror-crosshair { cursor: crosshair; }
.CodeMirror-line::selection, .CodeMirror-line > span::selection, .CodeMirror-line > span > span::selection { background: #d7d4f0; }
.CodeMirror-line::-moz-selection, .CodeMirror-line > span::-moz-selection, .CodeMirror-line > span > span::-moz-selection { background: #d7d4f0; }

.cm-searching {
  background-color: #ffa;
  background-color: rgba(255, 255, 0, .4);
}

/* Used to force a border model for a node */
.cm-force-border { padding-right: .1px; }

@media print {
  /* Hide the cursor when printing */
  .CodeMirror div.CodeMirror-cursors {
    visibility: hidden;
  }
}

/* See issue #2901 */
.cm-tab-wrap-hack:after { content: ''; }

/* Help users use markselection to safely style text background */
span.CodeMirror-selectedtext { background: none; }

.CodeMirror-dialog {
  position: absolute;
  left: 0; right: 0;
  background: inherit;
  z-index: 15;
  padding: .1em .8em;
  overflow: hidden;
  color: inherit;
}

.CodeMirror-dialog-top {
  border-bottom: 1px solid #eee;
  top: 0;
}

.CodeMirror-dialog-bottom {
  border-top: 1px solid #eee;
  bottom: 0;
}

.CodeMirror-dialog input {
  border: none;
  outline: none;
  background: transparent;
  width: 20em;
  color: inherit;
  font-family: monospace;
}

.CodeMirror-dialog button {
  font-size: 70%;
}

.CodeMirror-foldmarker {
  color: blue;
  text-shadow: #b9f 1px 1px 2px, #b9f -1px -1px 2px, #b9f 1px -1px 2px, #b9f -1px 1px 2px;
  font-family: arial;
  line-height: .3;
  cursor: pointer;
}
.CodeMirror-foldgutter {
  width: .7em;
}
.CodeMirror-foldgutter-open,
.CodeMirror-foldgutter-folded {
  cursor: pointer;
}
.CodeMirror-foldgutter-open:after {
  content: "\25BE";
}
.CodeMirror-foldgutter-folded:after {
  content: "\25B8";
}

/*
  Name:       material
  Author:     Mattia Astorino (http://github.com/equinusocio)
  Website:    https://material-theme.site/
*/

.cm-s-material.CodeMirror {
  background-color: #263238;
  color: #EEFFFF;
}

.cm-s-material .CodeMirror-gutters {
  background: #263238;
  color: #546E7A;
  border: none;
}

.cm-s-material .CodeMirror-guttermarker,
.cm-s-material .CodeMirror-guttermarker-subtle,
.cm-s-material .CodeMirror-linenumber {
  color: #546E7A;
}

.cm-s-material .CodeMirror-cursor {
  border-left: 1px solid #FFCC00;
}

.cm-s-material div.CodeMirror-selected {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material.CodeMirror-focused div.CodeMirror-selected {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material .CodeMirror-line::selection,
.cm-s-material .CodeMirror-line>span::selection,
.cm-s-material .CodeMirror-line>span>span::selection {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material .CodeMirror-line::-moz-selection,
.cm-s-material .CodeMirror-line>span::-moz-selection,
.cm-s-material .CodeMirror-line>span>span::-moz-selection {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material .CodeMirror-activeline-background {
  background: rgba(0, 0, 0, 0.5);
}

.cm-s-material .cm-keyword {
  color: #C792EA;
}

.cm-s-material .cm-operator {
  color: #89DDFF;
}

.cm-s-material .cm-variable-2 {
  color: #EEFFFF;
}

.cm-s-material .cm-variable-3,
.cm-s-material .cm-type {
  color: #f07178;
}

.cm-s-material .cm-builtin {
  color: #FFCB6B;
}

.cm-s-material .cm-atom {
  color: #F78C6C;
}

.cm-s-material .cm-number {
  color: #FF5370;
}

.cm-s-material .cm-def {
  color: #82AAFF;
}

.cm-s-material .cm-string {
  color: #C3E88D;
}

.cm-s-material .cm-string-2 {
  color: #f07178;
}

.cm-s-material .cm-comment {
  color: #546E7A;
}

.cm-s-material .cm-variable {
  color: #f07178;
}

.cm-s-material .cm-tag {
  color: #FF5370;
}

.cm-s-material .cm-meta {
  color: #FFCB6B;
}

.cm-s-material .cm-attribute {
  color: #C792EA;
}

.cm-s-material .cm-property {
  color: #C792EA;
}

.cm-s-material .cm-qualifier {
  color: #DECB6B;
}

.cm-s-material .cm-variable-3,
.cm-s-material .cm-type {
  color: #DECB6B;
}


.cm-s-material .cm-error {
  color: rgba(255, 255, 255, 1.0);
  background-color: #FF5370;
}

.cm-s-material .CodeMirror-matchingbracket {
  text-decoration: underline;
  color: white !important;
}
/**
 * "
 *  Using Zenburn color palette from the Emacs Zenburn Theme
 *  https://github.com/bbatsov/zenburn-emacs/blob/master/zenburn-theme.el
 *
 *  Also using parts of https://github.com/xavi/coderay-lighttable-theme
 * "
 * From: https://github.com/wisenomad/zenburn-lighttable-theme/blob/master/zenburn.css
 */

.cm-s-zenburn .CodeMirror-gutters { background: #3f3f3f !important; }
.cm-s-zenburn .CodeMirror-foldgutter-open, .CodeMirror-foldgutter-folded { color: #999; }
.cm-s-zenburn .CodeMirror-cursor { border-left: 1px solid white; }
.cm-s-zenburn { background-color: #3f3f3f; color: #dcdccc; }
.cm-s-zenburn span.cm-builtin { color: #dcdccc; font-weight: bold; }
.cm-s-zenburn span.cm-comment { color: #7f9f7f; }
.cm-s-zenburn span.cm-keyword { color: #f0dfaf; font-weight: bold; }
.cm-s-zenburn span.cm-atom { color: #bfebbf; }
.cm-s-zenburn span.cm-def { color: #dcdccc; }
.cm-s-zenburn span.cm-variable { color: #dfaf8f; }
.cm-s-zenburn span.cm-variable-2 { color: #dcdccc; }
.cm-s-zenburn span.cm-string { color: #cc9393; }
.cm-s-zenburn span.cm-string-2 { color: #cc9393; }
.cm-s-zenburn span.cm-number { color: #dcdccc; }
.cm-s-zenburn span.cm-tag { color: #93e0e3; }
.cm-s-zenburn span.cm-property { color: #dfaf8f; }
.cm-s-zenburn span.cm-attribute { color: #dfaf8f; }
.cm-s-zenburn span.cm-qualifier { color: #7cb8bb; }
.cm-s-zenburn span.cm-meta { color: #f0dfaf; }
.cm-s-zenburn span.cm-header { color: #f0efd0; }
.cm-s-zenburn span.cm-operator { color: #f0efd0; }
.cm-s-zenburn span.CodeMirror-matchingbracket { box-sizing: border-box; background: transparent; border-bottom: 1px solid; }
.cm-s-zenburn span.CodeMirror-nonmatchingbracket { border-bottom: 1px solid; background: none; }
.cm-s-zenburn .CodeMirror-activeline { background: #000000; }
.cm-s-zenburn .CodeMirror-activeline-background { background: #000000; }
.cm-s-zenburn div.CodeMirror-selected { background: #545454; }
.cm-s-zenburn .CodeMirror-focused div.CodeMirror-selected { background: #4f4f4f; }

.cm-s-abcdef.CodeMirror { background: #0f0f0f; color: #defdef; }
.cm-s-abcdef div.CodeMirror-selected { background: #515151; }
.cm-s-abcdef .CodeMirror-line::selection, .cm-s-abcdef .CodeMirror-line > span::selection, .cm-s-abcdef .CodeMirror-line > span > span::selection { background: rgba(56, 56, 56, 0.99); }
.cm-s-abcdef .CodeMirror-line::-moz-selection, .cm-s-abcdef .CodeMirror-line > span::-moz-selection, .cm-s-abcdef .CodeMirror-line > span > span::-moz-selection { background: rgba(56, 56, 56, 0.99); }
.cm-s-abcdef .CodeMirror-gutters { background: #555; border-right: 2px solid #314151; }
.cm-s-abcdef .CodeMirror-guttermarker { color: #222; }
.cm-s-abcdef .CodeMirror-guttermarker-subtle { color: azure; }
.cm-s-abcdef .CodeMirror-linenumber { color: #FFFFFF; }
.cm-s-abcdef .CodeMirror-cursor { border-left: 1px solid #00FF00; }

.cm-s-abcdef span.cm-keyword { color: darkgoldenrod; font-weight: bold; }
.cm-s-abcdef span.cm-atom { color: #77F; }
.cm-s-abcdef span.cm-number { color: violet; }
.cm-s-abcdef span.cm-def { color: #fffabc; }
.cm-s-abcdef span.cm-variable { color: #abcdef; }
.cm-s-abcdef span.cm-variable-2 { color: #cacbcc; }
.cm-s-abcdef span.cm-variable-3, .cm-s-abcdef span.cm-type { color: #def; }
.cm-s-abcdef span.cm-property { color: #fedcba; }
.cm-s-abcdef span.cm-operator { color: #ff0; }
.cm-s-abcdef span.cm-comment { color: #7a7b7c; font-style: italic;}
.cm-s-abcdef span.cm-string { color: #2b4; }
.cm-s-abcdef span.cm-meta { color: #C9F; }
.cm-s-abcdef span.cm-qualifier { color: #FFF700; }
.cm-s-abcdef span.cm-builtin { color: #30aabc; }
.cm-s-abcdef span.cm-bracket { color: #8a8a8a; }
.cm-s-abcdef span.cm-tag { color: #FFDD44; }
.cm-s-abcdef span.cm-attribute { color: #DDFF00; }
.cm-s-abcdef span.cm-error { color: #FF0000; }
.cm-s-abcdef span.cm-header { color: aquamarine; font-weight: bold; }
.cm-s-abcdef span.cm-link { color: blueviolet; }

.cm-s-abcdef .CodeMirror-activeline-background { background: #314151; }

/*

    Name:       Base16 Default Light
    Author:     Chris Kempson (http://chriskempson.com)

    CodeMirror template by Jan T. Sott (https://github.com/idleberg/base16-codemirror)
    Original Base16 color scheme by Chris Kempson (https://github.com/chriskempson/base16)

*/

.cm-s-base16-light.CodeMirror { background: #f5f5f5; color: #202020; }
.cm-s-base16-light div.CodeMirror-selected { background: #e0e0e0; }
.cm-s-base16-light .CodeMirror-line::selection, .cm-s-base16-light .CodeMirror-line > span::selection, .cm-s-base16-light .CodeMirror-line > span > span::selection { background: #e0e0e0; }
.cm-s-base16-light .CodeMirror-line::-moz-selection, .cm-s-base16-light .CodeMirror-line > span::-moz-selection, .cm-s-base16-light .CodeMirror-line > span > span::-moz-selection { background: #e0e0e0; }
.cm-s-base16-light .CodeMirror-gutters { background: #f5f5f5; border-right: 0px; }
.cm-s-base16-light .CodeMirror-guttermarker { color: #ac4142; }
.cm-s-base16-light .CodeMirror-guttermarker-subtle { color: #b0b0b0; }
.cm-s-base16-light .CodeMirror-linenumber { color: #b0b0b0; }
.cm-s-base16-light .CodeMirror-cursor { border-left: 1px solid #505050; }

.cm-s-base16-light span.cm-comment { color: #8f5536; }
.cm-s-base16-light span.cm-atom { color: #aa759f; }
.cm-s-base16-light span.cm-number { color: #aa759f; }

.cm-s-base16-light span.cm-property, .cm-s-base16-light span.cm-attribute { color: #90a959; }
.cm-s-base16-light span.cm-keyword { color: #ac4142; }
.cm-s-base16-light span.cm-string { color: #f4bf75; }

.cm-s-base16-light span.cm-variable { color: #90a959; }
.cm-s-base16-light span.cm-variable-2 { color: #6a9fb5; }
.cm-s-base16-light span.cm-def { color: #d28445; }
.cm-s-base16-light span.cm-bracket { color: #202020; }
.cm-s-base16-light span.cm-tag { color: #ac4142; }
.cm-s-base16-light span.cm-link { color: #aa759f; }
.cm-s-base16-light span.cm-error { background: #ac4142; color: #505050; }

.cm-s-base16-light .CodeMirror-activeline-background { background: #DDDCDC; }
.cm-s-base16-light .CodeMirror-matchingbracket { color: #f5f5f5 !important; background-color: #6A9FB5 !important}

/*

    Name:       Base16 Default Dark
    Author:     Chris Kempson (http://chriskempson.com)

    CodeMirror template by Jan T. Sott (https://github.com/idleberg/base16-codemirror)
    Original Base16 color scheme by Chris Kempson (https://github.com/chriskempson/base16)

*/

.cm-s-base16-dark.CodeMirror { background: #151515; color: #e0e0e0; }
.cm-s-base16-dark div.CodeMirror-selected { background: #303030; }
.cm-s-base16-dark .CodeMirror-line::selection, .cm-s-base16-dark .CodeMirror-line > span::selection, .cm-s-base16-dark .CodeMirror-line > span > span::selection { background: rgba(48, 48, 48, .99); }
.cm-s-base16-dark .CodeMirror-line::-moz-selection, .cm-s-base16-dark .CodeMirror-line > span::-moz-selection, .cm-s-base16-dark .CodeMirror-line > span > span::-moz-selection { background: rgba(48, 48, 48, .99); }
.cm-s-base16-dark .CodeMirror-gutters { background: #151515; border-right: 0px; }
.cm-s-base16-dark .CodeMirror-guttermarker { color: #ac4142; }
.cm-s-base16-dark .CodeMirror-guttermarker-subtle { color: #505050; }
.cm-s-base16-dark .CodeMirror-linenumber { color: #505050; }
.cm-s-base16-dark .CodeMirror-cursor { border-left: 1px solid #b0b0b0; }

.cm-s-base16-dark span.cm-comment { color: #8f5536; }
.cm-s-base16-dark span.cm-atom { color: #aa759f; }
.cm-s-base16-dark span.cm-number { color: #aa759f; }

.cm-s-base16-dark span.cm-property, .cm-s-base16-dark span.cm-attribute { color: #90a959; }
.cm-s-base16-dark span.cm-keyword { color: #ac4142; }
.cm-s-base16-dark span.cm-string { color: #f4bf75; }

.cm-s-base16-dark span.cm-variable { color: #90a959; }
.cm-s-base16-dark span.cm-variable-2 { color: #6a9fb5; }
.cm-s-base16-dark span.cm-def { color: #d28445; }
.cm-s-base16-dark span.cm-bracket { color: #e0e0e0; }
.cm-s-base16-dark span.cm-tag { color: #ac4142; }
.cm-s-base16-dark span.cm-link { color: #aa759f; }
.cm-s-base16-dark span.cm-error { background: #ac4142; color: #b0b0b0; }

.cm-s-base16-dark .CodeMirror-activeline-background { background: #202020; }
.cm-s-base16-dark .CodeMirror-matchingbracket { text-decoration: underline; color: white !important; }

/*

    Name:       dracula
    Author:     Michael Kaminsky (http://github.com/mkaminsky11)

    Original dracula color scheme by Zeno Rocha (https://github.com/zenorocha/dracula-theme)

*/


.cm-s-dracula.CodeMirror, .cm-s-dracula .CodeMirror-gutters {
  background-color: #282a36 !important;
  color: #f8f8f2 !important;
  border: none;
}
.cm-s-dracula .CodeMirror-gutters { color: #282a36; }
.cm-s-dracula .CodeMirror-cursor { border-left: solid thin #f8f8f0; }
.cm-s-dracula .CodeMirror-linenumber { color: #6D8A88; }
.cm-s-dracula .CodeMirror-selected { background: rgba(255, 255, 255, 0.10); }
.cm-s-dracula .CodeMirror-line::selection, .cm-s-dracula .CodeMirror-line > span::selection, .cm-s-dracula .CodeMirror-line > span > span::selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-dracula .CodeMirror-line::-moz-selection, .cm-s-dracula .CodeMirror-line > span::-moz-selection, .cm-s-dracula .CodeMirror-line > span > span::-moz-selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-dracula span.cm-comment { color: #6272a4; }
.cm-s-dracula span.cm-string, .cm-s-dracula span.cm-string-2 { color: #f1fa8c; }
.cm-s-dracula span.cm-number { color: #bd93f9; }
.cm-s-dracula span.cm-variable { color: #50fa7b; }
.cm-s-dracula span.cm-variable-2 { color: white; }
.cm-s-dracula span.cm-def { color: #50fa7b; }
.cm-s-dracula span.cm-operator { color: #ff79c6; }
.cm-s-dracula span.cm-keyword { color: #ff79c6; }
.cm-s-dracula span.cm-atom { color: #bd93f9; }
.cm-s-dracula span.cm-meta { color: #f8f8f2; }
.cm-s-dracula span.cm-tag { color: #ff79c6; }
.cm-s-dracula span.cm-attribute { color: #50fa7b; }
.cm-s-dracula span.cm-qualifier { color: #50fa7b; }
.cm-s-dracula span.cm-property { color: #66d9ef; }
.cm-s-dracula span.cm-builtin { color: #50fa7b; }
.cm-s-dracula span.cm-variable-3, .cm-s-dracula span.cm-type { color: #ffb86c; }

.cm-s-dracula .CodeMirror-activeline-background { background: rgba(255,255,255,0.1); }
.cm-s-dracula .CodeMirror-matchingbracket { text-decoration: underline; color: white !important; }

/*

    Name:       Hopscotch
    Author:     Jan T. Sott

    CodeMirror template by Jan T. Sott (https://github.com/idleberg/base16-codemirror)
    Original Base16 color scheme by Chris Kempson (https://github.com/chriskempson/base16)

*/

.cm-s-hopscotch.CodeMirror {background: #322931; color: #d5d3d5;}
.cm-s-hopscotch div.CodeMirror-selected {background: #433b42 !important;}
.cm-s-hopscotch .CodeMirror-gutters {background: #322931; border-right: 0px;}
.cm-s-hopscotch .CodeMirror-linenumber {color: #797379;}
.cm-s-hopscotch .CodeMirror-cursor {border-left: 1px solid #989498 !important;}

.cm-s-hopscotch span.cm-comment {color: #b33508;}
.cm-s-hopscotch span.cm-atom {color: #c85e7c;}
.cm-s-hopscotch span.cm-number {color: #c85e7c;}

.cm-s-hopscotch span.cm-property, .cm-s-hopscotch span.cm-attribute {color: #8fc13e;}
.cm-s-hopscotch span.cm-keyword {color: #dd464c;}
.cm-s-hopscotch span.cm-string {color: #fdcc59;}

.cm-s-hopscotch span.cm-variable {color: #8fc13e;}
.cm-s-hopscotch span.cm-variable-2 {color: #1290bf;}
.cm-s-hopscotch span.cm-def {color: #fd8b19;}
.cm-s-hopscotch span.cm-error {background: #dd464c; color: #989498;}
.cm-s-hopscotch span.cm-bracket {color: #d5d3d5;}
.cm-s-hopscotch span.cm-tag {color: #dd464c;}
.cm-s-hopscotch span.cm-link {color: #c85e7c;}

.cm-s-hopscotch .CodeMirror-matchingbracket { text-decoration: underline; color: white !important;}
.cm-s-hopscotch .CodeMirror-activeline-background { background: #302020; }

/****************************************************************/
/*   Based on mbonaci's Brackets mbo theme                      */
/*   https://github.com/mbonaci/global/blob/master/Mbo.tmTheme  */
/*   Create your own: http://tmtheme-editor.herokuapp.com       */
/****************************************************************/

.cm-s-mbo.CodeMirror { background: #2c2c2c; color: #ffffec; }
.cm-s-mbo div.CodeMirror-selected { background: #716C62; }
.cm-s-mbo .CodeMirror-line::selection, .cm-s-mbo .CodeMirror-line > span::selection, .cm-s-mbo .CodeMirror-line > span > span::selection { background: rgba(113, 108, 98, .99); }
.cm-s-mbo .CodeMirror-line::-moz-selection, .cm-s-mbo .CodeMirror-line > span::-moz-selection, .cm-s-mbo .CodeMirror-line > span > span::-moz-selection { background: rgba(113, 108, 98, .99); }
.cm-s-mbo .CodeMirror-gutters { background: #4e4e4e; border-right: 0px; }
.cm-s-mbo .CodeMirror-guttermarker { color: white; }
.cm-s-mbo .CodeMirror-guttermarker-subtle { color: grey; }
.cm-s-mbo .CodeMirror-linenumber { color: #dadada; }
.cm-s-mbo .CodeMirror-cursor { border-left: 1px solid #ffffec; }

.cm-s-mbo span.cm-comment { color: #95958a; }
.cm-s-mbo span.cm-atom { color: #00a8c6; }
.cm-s-mbo span.cm-number { color: #00a8c6; }

.cm-s-mbo span.cm-property, .cm-s-mbo span.cm-attribute { color: #9ddfe9; }
.cm-s-mbo span.cm-keyword { color: #ffb928; }
.cm-s-mbo span.cm-string { color: #ffcf6c; }
.cm-s-mbo span.cm-string.cm-property { color: #ffffec; }

.cm-s-mbo span.cm-variable { color: #ffffec; }
.cm-s-mbo span.cm-variable-2 { color: #00a8c6; }
.cm-s-mbo span.cm-def { color: #ffffec; }
.cm-s-mbo span.cm-bracket { color: #fffffc; font-weight: bold; }
.cm-s-mbo span.cm-tag { color: #9ddfe9; }
.cm-s-mbo span.cm-link { color: #f54b07; }
.cm-s-mbo span.cm-error { border-bottom: #636363; color: #ffffec; }
.cm-s-mbo span.cm-qualifier { color: #ffffec; }

.cm-s-mbo .CodeMirror-activeline-background { background: #494b41; }
.cm-s-mbo .CodeMirror-matchingbracket { color: #ffb928 !important; }
.cm-s-mbo .CodeMirror-matchingtag { background: rgba(255, 255, 255, .37); }

/*
  MDN-LIKE Theme - Mozilla
  Ported to CodeMirror by Peter Kroon <plakroon@gmail.com>
  Report bugs/issues here: https://github.com/codemirror/CodeMirror/issues
  GitHub: @peterkroon

  The mdn-like theme is inspired on the displayed code examples at: https://developer.mozilla.org/en-US/docs/Web/CSS/animation

*/
.cm-s-mdn-like.CodeMirror { color: #999; background-color: #fff; }
.cm-s-mdn-like div.CodeMirror-selected { background: #cfc; }
.cm-s-mdn-like .CodeMirror-line::selection, .cm-s-mdn-like .CodeMirror-line > span::selection, .cm-s-mdn-like .CodeMirror-line > span > span::selection { background: #cfc; }
.cm-s-mdn-like .CodeMirror-line::-moz-selection, .cm-s-mdn-like .CodeMirror-line > span::-moz-selection, .cm-s-mdn-like .CodeMirror-line > span > span::-moz-selection { background: #cfc; }

.cm-s-mdn-like .CodeMirror-gutters { background: #f8f8f8; border-left: 6px solid rgba(0,83,159,0.65); color: #333; }
.cm-s-mdn-like .CodeMirror-linenumber { color: #aaa; padding-left: 8px; }
.cm-s-mdn-like .CodeMirror-cursor { border-left: 2px solid #222; }

.cm-s-mdn-like .cm-keyword { color: #6262FF; }
.cm-s-mdn-like .cm-atom { color: #F90; }
.cm-s-mdn-like .cm-number { color:  #ca7841; }
.cm-s-mdn-like .cm-def { color: #8DA6CE; }
.cm-s-mdn-like span.cm-variable-2, .cm-s-mdn-like span.cm-tag { color: #690; }
.cm-s-mdn-like span.cm-variable-3, .cm-s-mdn-like span.cm-def, .cm-s-mdn-like span.cm-type { color: #07a; }

.cm-s-mdn-like .cm-variable { color: #07a; }
.cm-s-mdn-like .cm-property { color: #905; }
.cm-s-mdn-like .cm-qualifier { color: #690; }

.cm-s-mdn-like .cm-operator { color: #cda869; }
.cm-s-mdn-like .cm-comment { color:#777; font-weight:normal; }
.cm-s-mdn-like .cm-string { color:#07a; font-style:italic; }
.cm-s-mdn-like .cm-string-2 { color:#bd6b18; } /*?*/
.cm-s-mdn-like .cm-meta { color: #000; } /*?*/
.cm-s-mdn-like .cm-builtin { color: #9B7536; } /*?*/
.cm-s-mdn-like .cm-tag { color: #997643; }
.cm-s-mdn-like .cm-attribute { color: #d6bb6d; } /*?*/
.cm-s-mdn-like .cm-header { color: #FF6400; }
.cm-s-mdn-like .cm-hr { color: #AEAEAE; }
.cm-s-mdn-like .cm-link { color:#ad9361; font-style:italic; text-decoration:none; }
.cm-s-mdn-like .cm-error { border-bottom: 1px solid red; }

div.cm-s-mdn-like .CodeMirror-activeline-background { background: #efefff; }
div.cm-s-mdn-like span.CodeMirror-matchingbracket { outline:1px solid grey; color: inherit; }

.cm-s-mdn-like.CodeMirror { background-image: url(data:image/png;base64,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); }

/*

    Name:       seti
    Author:     Michael Kaminsky (http://github.com/mkaminsky11)

    Original seti color scheme by Jesse Weed (https://github.com/jesseweed/seti-syntax)

*/


.cm-s-seti.CodeMirror {
  background-color: #151718 !important;
  color: #CFD2D1 !important;
  border: none;
}
.cm-s-seti .CodeMirror-gutters {
  color: #404b53;
  background-color: #0E1112;
  border: none;
}
.cm-s-seti .CodeMirror-cursor { border-left: solid thin #f8f8f0; }
.cm-s-seti .CodeMirror-linenumber { color: #6D8A88; }
.cm-s-seti.CodeMirror-focused div.CodeMirror-selected { background: rgba(255, 255, 255, 0.10); }
.cm-s-seti .CodeMirror-line::selection, .cm-s-seti .CodeMirror-line > span::selection, .cm-s-seti .CodeMirror-line > span > span::selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-seti .CodeMirror-line::-moz-selection, .cm-s-seti .CodeMirror-line > span::-moz-selection, .cm-s-seti .CodeMirror-line > span > span::-moz-selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-seti span.cm-comment { color: #41535b; }
.cm-s-seti span.cm-string, .cm-s-seti span.cm-string-2 { color: #55b5db; }
.cm-s-seti span.cm-number { color: #cd3f45; }
.cm-s-seti span.cm-variable { color: #55b5db; }
.cm-s-seti span.cm-variable-2 { color: #a074c4; }
.cm-s-seti span.cm-def { color: #55b5db; }
.cm-s-seti span.cm-keyword { color: #ff79c6; }
.cm-s-seti span.cm-operator { color: #9fca56; }
.cm-s-seti span.cm-keyword { color: #e6cd69; }
.cm-s-seti span.cm-atom { color: #cd3f45; }
.cm-s-seti span.cm-meta { color: #55b5db; }
.cm-s-seti span.cm-tag { color: #55b5db; }
.cm-s-seti span.cm-attribute { color: #9fca56; }
.cm-s-seti span.cm-qualifier { color: #9fca56; }
.cm-s-seti span.cm-property { color: #a074c4; }
.cm-s-seti span.cm-variable-3, .cm-s-seti span.cm-type { color: #9fca56; }
.cm-s-seti span.cm-builtin { color: #9fca56; }
.cm-s-seti .CodeMirror-activeline-background { background: #101213; }
.cm-s-seti .CodeMirror-matchingbracket { text-decoration: underline; color: white !important; }

/*
Solarized theme for code-mirror
http://ethanschoonover.com/solarized
*/

/*
Solarized color palette
http://ethanschoonover.com/solarized/img/solarized-palette.png
*/

.solarized.base03 { color: #002b36; }
.solarized.base02 { color: #073642; }
.solarized.base01 { color: #586e75; }
.solarized.base00 { color: #657b83; }
.solarized.base0 { color: #839496; }
.solarized.base1 { color: #93a1a1; }
.solarized.base2 { color: #eee8d5; }
.solarized.base3  { color: #fdf6e3; }
.solarized.solar-yellow  { color: #b58900; }
.solarized.solar-orange  { color: #cb4b16; }
.solarized.solar-red { color: #dc322f; }
.solarized.solar-magenta { color: #d33682; }
.solarized.solar-violet  { color: #6c71c4; }
.solarized.solar-blue { color: #268bd2; }
.solarized.solar-cyan { color: #2aa198; }
.solarized.solar-green { color: #859900; }

/* Color scheme for code-mirror */

.cm-s-solarized {
  line-height: 1.45em;
  color-profile: sRGB;
  rendering-intent: auto;
}
.cm-s-solarized.cm-s-dark {
  color: #839496;
  background-color: #002b36;
  text-shadow: #002b36 0 1px;
}
.cm-s-solarized.cm-s-light {
  background-color: #fdf6e3;
  color: #657b83;
  text-shadow: #eee8d5 0 1px;
}

.cm-s-solarized .CodeMirror-widget {
  text-shadow: none;
}

.cm-s-solarized .cm-header { color: #586e75; }
.cm-s-solarized .cm-quote { color: #93a1a1; }

.cm-s-solarized .cm-keyword { color: #cb4b16; }
.cm-s-solarized .cm-atom { color: #d33682; }
.cm-s-solarized .cm-number { color: #d33682; }
.cm-s-solarized .cm-def { color: #2aa198; }

.cm-s-solarized .cm-variable { color: #839496; }
.cm-s-solarized .cm-variable-2 { color: #b58900; }
.cm-s-solarized .cm-variable-3, .cm-s-solarized .cm-type { color: #6c71c4; }

.cm-s-solarized .cm-property { color: #2aa198; }
.cm-s-solarized .cm-operator { color: #6c71c4; }

.cm-s-solarized .cm-comment { color: #586e75; font-style:italic; }

.cm-s-solarized .cm-string { color: #859900; }
.cm-s-solarized .cm-string-2 { color: #b58900; }

.cm-s-solarized .cm-meta { color: #859900; }
.cm-s-solarized .cm-qualifier { color: #b58900; }
.cm-s-solarized .cm-builtin { color: #d33682; }
.cm-s-solarized .cm-bracket { color: #cb4b16; }
.cm-s-solarized .CodeMirror-matchingbracket { color: #859900; }
.cm-s-solarized .CodeMirror-nonmatchingbracket { color: #dc322f; }
.cm-s-solarized .cm-tag { color: #93a1a1; }
.cm-s-solarized .cm-attribute { color: #2aa198; }
.cm-s-solarized .cm-hr {
  color: transparent;
  border-top: 1px solid #586e75;
  display: block;
}
.cm-s-solarized .cm-link { color: #93a1a1; cursor: pointer; }
.cm-s-solarized .cm-special { color: #6c71c4; }
.cm-s-solarized .cm-em {
  color: #999;
  text-decoration: underline;
  text-decoration-style: dotted;
}
.cm-s-solarized .cm-error,
.cm-s-solarized .cm-invalidchar {
  color: #586e75;
  border-bottom: 1px dotted #dc322f;
}

.cm-s-solarized.cm-s-dark div.CodeMirror-selected { background: #073642; }
.cm-s-solarized.cm-s-dark.CodeMirror ::selection { background: rgba(7, 54, 66, 0.99); }
.cm-s-solarized.cm-s-dark .CodeMirror-line::-moz-selection, .cm-s-dark .CodeMirror-line > span::-moz-selection, .cm-s-dark .CodeMirror-line > span > span::-moz-selection { background: rgba(7, 54, 66, 0.99); }

.cm-s-solarized.cm-s-light div.CodeMirror-selected { background: #eee8d5; }
.cm-s-solarized.cm-s-light .CodeMirror-line::selection, .cm-s-light .CodeMirror-line > span::selection, .cm-s-light .CodeMirror-line > span > span::selection { background: #eee8d5; }
.cm-s-solarized.cm-s-light .CodeMirror-line::-moz-selection, .cm-s-ligh .CodeMirror-line > span::-moz-selection, .cm-s-ligh .CodeMirror-line > span > span::-moz-selection { background: #eee8d5; }

/* Editor styling */



/* Little shadow on the view-port of the buffer view */
.cm-s-solarized.CodeMirror {
  -moz-box-shadow: inset 7px 0 12px -6px #000;
  -webkit-box-shadow: inset 7px 0 12px -6px #000;
  box-shadow: inset 7px 0 12px -6px #000;
}

/* Remove gutter border */
.cm-s-solarized .CodeMirror-gutters {
  border-right: 0;
}

/* Gutter colors and line number styling based of color scheme (dark / light) */

/* Dark */
.cm-s-solarized.cm-s-dark .CodeMirror-gutters {
  background-color: #073642;
}

.cm-s-solarized.cm-s-dark .CodeMirror-linenumber {
  color: #586e75;
  text-shadow: #021014 0 -1px;
}

/* Light */
.cm-s-solarized.cm-s-light .CodeMirror-gutters {
  background-color: #eee8d5;
}

.cm-s-solarized.cm-s-light .CodeMirror-linenumber {
  color: #839496;
}

/* Common */
.cm-s-solarized .CodeMirror-linenumber {
  padding: 0 5px;
}
.cm-s-solarized .CodeMirror-guttermarker-subtle { color: #586e75; }
.cm-s-solarized.cm-s-dark .CodeMirror-guttermarker { color: #ddd; }
.cm-s-solarized.cm-s-light .CodeMirror-guttermarker { color: #cb4b16; }

.cm-s-solarized .CodeMirror-gutter .CodeMirror-gutter-text {
  color: #586e75;
}

/* Cursor */
.cm-s-solarized .CodeMirror-cursor { border-left: 1px solid #819090; }

/* Fat cursor */
.cm-s-solarized.cm-s-light.cm-fat-cursor .CodeMirror-cursor { background: #77ee77; }
.cm-s-solarized.cm-s-light .cm-animate-fat-cursor { background-color: #77ee77; }
.cm-s-solarized.cm-s-dark.cm-fat-cursor .CodeMirror-cursor { background: #586e75; }
.cm-s-solarized.cm-s-dark .cm-animate-fat-cursor { background-color: #586e75; }

/* Active line */
.cm-s-solarized.cm-s-dark .CodeMirror-activeline-background {
  background: rgba(255, 255, 255, 0.06);
}
.cm-s-solarized.cm-s-light .CodeMirror-activeline-background {
  background: rgba(0, 0, 0, 0.06);
}

.cm-s-the-matrix.CodeMirror { background: #000000; color: #00FF00; }
.cm-s-the-matrix div.CodeMirror-selected { background: #2D2D2D; }
.cm-s-the-matrix .CodeMirror-line::selection, .cm-s-the-matrix .CodeMirror-line > span::selection, .cm-s-the-matrix .CodeMirror-line > span > span::selection { background: rgba(45, 45, 45, 0.99); }
.cm-s-the-matrix .CodeMirror-line::-moz-selection, .cm-s-the-matrix .CodeMirror-line > span::-moz-selection, .cm-s-the-matrix .CodeMirror-line > span > span::-moz-selection { background: rgba(45, 45, 45, 0.99); }
.cm-s-the-matrix .CodeMirror-gutters { background: #060; border-right: 2px solid #00FF00; }
.cm-s-the-matrix .CodeMirror-guttermarker { color: #0f0; }
.cm-s-the-matrix .CodeMirror-guttermarker-subtle { color: white; }
.cm-s-the-matrix .CodeMirror-linenumber { color: #FFFFFF; }
.cm-s-the-matrix .CodeMirror-cursor { border-left: 1px solid #00FF00; }

.cm-s-the-matrix span.cm-keyword { color: #008803; font-weight: bold; }
.cm-s-the-matrix span.cm-atom { color: #3FF; }
.cm-s-the-matrix span.cm-number { color: #FFB94F; }
.cm-s-the-matrix span.cm-def { color: #99C; }
.cm-s-the-matrix span.cm-variable { color: #F6C; }
.cm-s-the-matrix span.cm-variable-2 { color: #C6F; }
.cm-s-the-matrix span.cm-variable-3, .cm-s-the-matrix span.cm-type { color: #96F; }
.cm-s-the-matrix span.cm-property { color: #62FFA0; }
.cm-s-the-matrix span.cm-operator { color: #999; }
.cm-s-the-matrix span.cm-comment { color: #CCCCCC; }
.cm-s-the-matrix span.cm-string { color: #39C; }
.cm-s-the-matrix span.cm-meta { color: #C9F; }
.cm-s-the-matrix span.cm-qualifier { color: #FFF700; }
.cm-s-the-matrix span.cm-builtin { color: #30a; }
.cm-s-the-matrix span.cm-bracket { color: #cc7; }
.cm-s-the-matrix span.cm-tag { color: #FFBD40; }
.cm-s-the-matrix span.cm-attribute { color: #FFF700; }
.cm-s-the-matrix span.cm-error { color: #FF0000; }

.cm-s-the-matrix .CodeMirror-activeline-background { background: #040; }

/*
Copyright (C) 2011 by MarkLogic Corporation
Author: Mike Brevoort <mike@brevoort.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
*/
.cm-s-xq-light span.cm-keyword { line-height: 1em; font-weight: bold; color: #5A5CAD; }
.cm-s-xq-light span.cm-atom { color: #6C8CD5; }
.cm-s-xq-light span.cm-number { color: #164; }
.cm-s-xq-light span.cm-def { text-decoration:underline; }
.cm-s-xq-light span.cm-variable { color: black; }
.cm-s-xq-light span.cm-variable-2 { color:black; }
.cm-s-xq-light span.cm-variable-3, .cm-s-xq-light span.cm-type { color: black; }
.cm-s-xq-light span.cm-property {}
.cm-s-xq-light span.cm-operator {}
.cm-s-xq-light span.cm-comment { color: #0080FF; font-style: italic; }
.cm-s-xq-light span.cm-string { color: red; }
.cm-s-xq-light span.cm-meta { color: yellow; }
.cm-s-xq-light span.cm-qualifier { color: grey; }
.cm-s-xq-light span.cm-builtin { color: #7EA656; }
.cm-s-xq-light span.cm-bracket { color: #cc7; }
.cm-s-xq-light span.cm-tag { color: #3F7F7F; }
.cm-s-xq-light span.cm-attribute { color: #7F007F; }
.cm-s-xq-light span.cm-error { color: #f00; }

.cm-s-xq-light .CodeMirror-activeline-background { background: #e8f2ff; }
.cm-s-xq-light .CodeMirror-matchingbracket { outline:1px solid grey;color:black !important;background:yellow; }

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.CodeMirror {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;
  /* Changed to auto to autogrow */
}

.CodeMirror pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* This causes https://github.com/jupyter/jupyterlab/issues/522 */
/* May not cause it not because we changed it! */
.CodeMirror-lines {
  padding: var(--jp-code-padding) 0;
}

.CodeMirror-linenumber {
  padding: 0 8px;
}

.jp-CodeMirrorEditor-static {
  margin: var(--jp-code-padding);
}

.jp-CodeMirrorEditor,
.jp-CodeMirrorEditor-static {
  cursor: text;
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.CodeMirror.jp-mod-readOnly .CodeMirror-cursor {
  display: none;
}

.CodeMirror-gutters {
  border-right: 1px solid var(--jp-border-color2);
  background-color: var(--jp-layout-color0);
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.CodeMirror-selectedtext.cm-searching {
  background-color: var(--jp-search-selected-match-background-color) !important;
  color: var(--jp-search-selected-match-color) !important;
}

.cm-searching {
  background-color: var(
    --jp-search-unselected-match-background-color
  ) !important;
  color: var(--jp-search-unselected-match-color) !important;
}

.CodeMirror-focused .CodeMirror-selected {
  background-color: var(--jp-editor-selected-focused-background);
}

.CodeMirror-selected {
  background-color: var(--jp-editor-selected-background);
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/**
 * Here is our jupyter theme for CodeMirror syntax highlighting
 * This is used in our marked.js syntax highlighting and CodeMirror itself
 * The string "jupyter" is set in ../codemirror/widget.DEFAULT_CODEMIRROR_THEME
 * This came from the classic notebook, which came form highlight.js/GitHub
 */

/**
 * CodeMirror themes are handling the background/color in this way. This works
 * fine for CodeMirror editors outside the notebook, but the notebook styles
 * these things differently.
 */
.CodeMirror.cm-s-jupyter {
  background: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* In the notebook, we want this styling to be handled by its container */
.jp-CodeConsole .CodeMirror.cm-s-jupyter,
.jp-Notebook .CodeMirror.cm-s-jupyter {
  background: transparent;
}

.cm-s-jupyter .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}
.cm-s-jupyter span.cm-keyword {
  color: var(--jp-mirror-editor-keyword-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-atom {
  color: var(--jp-mirror-editor-atom-color);
}
.cm-s-jupyter span.cm-number {
  color: var(--jp-mirror-editor-number-color);
}
.cm-s-jupyter span.cm-def {
  color: var(--jp-mirror-editor-def-color);
}
.cm-s-jupyter span.cm-variable {
  color: var(--jp-mirror-editor-variable-color);
}
.cm-s-jupyter span.cm-variable-2 {
  color: var(--jp-mirror-editor-variable-2-color);
}
.cm-s-jupyter span.cm-variable-3 {
  color: var(--jp-mirror-editor-variable-3-color);
}
.cm-s-jupyter span.cm-punctuation {
  color: var(--jp-mirror-editor-punctuation-color);
}
.cm-s-jupyter span.cm-property {
  color: var(--jp-mirror-editor-property-color);
}
.cm-s-jupyter span.cm-operator {
  color: var(--jp-mirror-editor-operator-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-comment {
  color: var(--jp-mirror-editor-comment-color);
  font-style: italic;
}
.cm-s-jupyter span.cm-string {
  color: var(--jp-mirror-editor-string-color);
}
.cm-s-jupyter span.cm-string-2 {
  color: var(--jp-mirror-editor-string-2-color);
}
.cm-s-jupyter span.cm-meta {
  color: var(--jp-mirror-editor-meta-color);
}
.cm-s-jupyter span.cm-qualifier {
  color: var(--jp-mirror-editor-qualifier-color);
}
.cm-s-jupyter span.cm-builtin {
  color: var(--jp-mirror-editor-builtin-color);
}
.cm-s-jupyter span.cm-bracket {
  color: var(--jp-mirror-editor-bracket-color);
}
.cm-s-jupyter span.cm-tag {
  color: var(--jp-mirror-editor-tag-color);
}
.cm-s-jupyter span.cm-attribute {
  color: var(--jp-mirror-editor-attribute-color);
}
.cm-s-jupyter span.cm-header {
  color: var(--jp-mirror-editor-header-color);
}
.cm-s-jupyter span.cm-quote {
  color: var(--jp-mirror-editor-quote-color);
}
.cm-s-jupyter span.cm-link {
  color: var(--jp-mirror-editor-link-color);
}
.cm-s-jupyter span.cm-error {
  color: var(--jp-mirror-editor-error-color);
}
.cm-s-jupyter span.cm-hr {
  color: #999;
}

.cm-s-jupyter span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}

.cm-s-jupyter .CodeMirror-activeline-background,
.cm-s-jupyter .CodeMirror-gutter {
  background-color: var(--jp-layout-color2);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0px;
  padding: 0px;
  line-height: normal;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}
.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}
.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}
.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}
.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}
.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}
.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}
.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
}
.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
}
.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
}
.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
}
.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
}
.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
}
.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
}
.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}
.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}
.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}
.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}
.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}
.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}
.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}
.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
}
.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
}
.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
}
.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
}
.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
}
.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
}
.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
}
.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}
.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}
.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0em;
}

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: 12px;
  table-layout: fixed;
  margin-left: auto;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon table {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0px;
}

.jp-RenderedHTMLCommon p {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}
/* ...or leave it untouched if they don't */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-dark-background {
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-light-background {
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}
.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}
.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}
.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}
.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}
.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}
.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}
.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}
.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: 0.8em;
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser {
  display: flex;
  flex-direction: column;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  border-bottom: none;
  height: auto;
  margin: var(--jp-toolbar-header-margin);
  box-shadow: none;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 4px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0px 2px;
  padding: 0px 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0px;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar.jp-Toolbar {
  padding: 0px;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  justify-content: space-evenly;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-Toolbar-item {
  flex: 1;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-ToolbarButtonComponent {
  width: 100%;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px 12px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-item.jp-mod-selected {
  color: white;
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon:before {
  color: limegreen;
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0px;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-DirListing-deadSpace {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

.jp-FileDialog.jp-mod-conflict input {
  color: red;
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
}

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: flex;
  flex-direction: row;
}

.jp-OutputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-OutputArea-output {
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea-child .jp-OutputArea-output {
  flex-grow: 1;
  flex-shrink: 1;
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0px;
  padding: 0px;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0px;
  flex: 1 1 auto;
}

.jp-OutputArea-executeResult.jp-RenderedText {
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-OutputArea-stdin {
  line-height: var(--jp-code-line-height);
  padding-top: var(--jp-code-padding);
  display: flex;
}

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;
  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0px;
  bottom: 0px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0px;
  width: 100%;
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: flex;
  flex-direction: row;
}

.jp-InputArea-editor {
  flex: 1 1 auto;
}

.jp-InputArea-editor {
  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0px;
  background: var(--jp-cell-editor-background);
}

.jp-InputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: flex;
  flex-direction: row;
  flex: 1 1 auto;
}

.jp-Placeholder-prompt {
  box-sizing: border-box;
}

.jp-Placeholder-content {
  flex: 1 1 auto;
  border: none;
  background: transparent;
  height: 20px;
  box-sizing: border-box;
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0px;
  margin: 0px;
  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 200px;
  box-shadow: inset 0 0 6px 2px rgba(0, 0, 0, 0.3);
  margin-left: var(--jp-private-cell-scrolling-output-offset);
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  flex: 0 0
    calc(
      var(--jp-cell-prompt-width) -
        var(--jp-private-cell-scrolling-output-offset)
    );
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  flex: 1 1 auto;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: 2px;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: flex;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0px;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-NotebookTools-tool {
  padding: 0px 12px 0 12px;
}

.jp-ActiveCellTool {
  padding: 12px;
  background-color: var(--jp-layout-color1);
  border-top: none !important;
}

.jp-ActiveCellTool .jp-InputArea-prompt {
  flex: 0 0 auto;
  padding-left: 0px;
}

.jp-ActiveCellTool .jp-InputArea-editor {
  flex: 1 1 auto;
  background: var(--jp-cell-editor-background);
  border-color: var(--jp-cell-editor-border-color);
}

.jp-ActiveCellTool .jp-InputArea-editor .CodeMirror {
  background: transparent;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0px 12px 0px;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label {
  line-height: 1.4;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

</style>

    <style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0px 2px 1px -1px var(--jp-shadow-umbra-color),
    0px 1px 1px 0px var(--jp-shadow-penumbra-color),
    0px 1px 3px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0px 3px 1px -2px var(--jp-shadow-umbra-color),
    0px 2px 2px 0px var(--jp-shadow-penumbra-color),
    0px 1px 5px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0px 2px 4px -1px var(--jp-shadow-umbra-color),
    0px 4px 5px 0px var(--jp-shadow-penumbra-color),
    0px 1px 10px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0px 3px 5px -1px var(--jp-shadow-umbra-color),
    0px 6px 10px 0px var(--jp-shadow-penumbra-color),
    0px 1px 18px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0px 5px 5px -3px var(--jp-shadow-umbra-color),
    0px 8px 10px 1px var(--jp-shadow-penumbra-color),
    0px 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0px 7px 8px -4px var(--jp-shadow-umbra-color),
    0px 12px 17px 2px var(--jp-shadow-penumbra-color),
    0px 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0px 8px 10px -5px var(--jp-shadow-umbra-color),
    0px 16px 24px 2px var(--jp-shadow-penumbra-color),
    0px 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0px 10px 13px -6px var(--jp-shadow-umbra-color),
    0px 20px 31px 3px var(--jp-shadow-penumbra-color),
    0px 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0px 11px 15px -7px var(--jp-shadow-umbra-color),
    0px 24px 38px 3px var(--jp-shadow-penumbra-color),
    0px 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;

  --jp-ui-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica,
    Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;

  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);

  --jp-content-link-color: var(--md-blue-700);

  --jp-content-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: Menlo, Consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-700);
  --jp-brand-color1: var(--md-blue-500);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);

  --jp-accent-color0: var(--md-green-700);
  --jp-accent-color1: var(--md-green-500);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-700);
  --jp-warn-color1: var(--md-orange-500);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);

  --jp-error-color0: var(--md-red-700);
  --jp-error-color1: var(--md-red-500);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);

  --jp-success-color0: var(--md-green-700);
  --jp-success-color1: var(--md-green-500);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);

  --jp-info-color0: var(--md-cyan-700);
  --jp-info-color1: var(--md-cyan-500);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;

  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;

  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);

  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: 'Source Code Pro', monospace;
  --jp-cell-prompt-letter-spacing: 0px;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);
  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;
  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0px 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-border-color1);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: #05a;
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #aa22ff;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #aa22ff;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 180px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);
}
</style>

<style type="text/css">
a.anchor-link {
   display: none;
}
.highlight  {
    margin: 0.4em;
}

/* Input area styling */
.jp-InputArea {
    overflow: hidden;
}

.jp-InputArea-editor {
    overflow: hidden;
}

@media print {
  body {
    margin: 0;
  }
}
</style>



<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-MML-AM_CHTML-full,Safe"> </script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                CommonHTML: {
                    linebreaks: { 
                    automatic: true 
                    }
                },
                "HTML-CSS": {
                    linebreaks: { 
                    automatic: true 
                    }
                }
            });
        
            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
    <!-- End of mathjax configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">

<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>STAT 6543<br>
HW 2</strong><br>
Sheri Osborn</p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>HW 2 Assignment</p>
<p>Chapter 03 (page 120): 2, 9, 10, 12</p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>2. Carefully explain the differences between the KNN classifier and KNN
regression methods.</strong></p>
<p style="color:blue;">
KNN models are implementations based on the premise that things that share similar features tend to be similar.  In classification, KNN classification puts a new datapoint with those datapoints that are closest in characteristic(s) and therefore is qualitative in nature.  KNN approach for regressions is where we want to place a value rather than a classification.  It approximates the association between independent variables and the continuous outcome by averaging the observations in the same neighborhood. It stores all available cases and predicts the numerical target based on a similarity measure (e.g., distance functions).</p>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>9. This question involves the use of multiple linear regression on the Auto data set.</strong></p>
<ol>
<li>Produce a scatterplot matrix which includes all of the variables in the data set.</li>
</ol>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[16]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="nf">library</span><span class="p">(</span><span class="n">ISLR</span><span class="p">)</span>
<span class="n">car</span> <span class="o">=</span> <span class="nf">as.data.frame</span><span class="p">(</span><span class="n">Auto</span><span class="p">)</span>
<span class="nf">dim</span><span class="p">(</span><span class="n">car</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">car</span><span class="p">)</span>
<span class="nf">attach</span><span class="p">(</span><span class="n">car</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<ol class=list-inline>
	<li>392</li>
	<li>9</li>
</ol>

</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>      mpg          cylinders      displacement     horsepower        weight    
 Min.   : 9.00   Min.   :3.000   Min.   : 68.0   Min.   : 46.0   Min.   :1613  
 1st Qu.:17.00   1st Qu.:4.000   1st Qu.:105.0   1st Qu.: 75.0   1st Qu.:2225  
 Median :22.75   Median :4.000   Median :151.0   Median : 93.5   Median :2804  
 Mean   :23.45   Mean   :5.472   Mean   :194.4   Mean   :104.5   Mean   :2978  
 3rd Qu.:29.00   3rd Qu.:8.000   3rd Qu.:275.8   3rd Qu.:126.0   3rd Qu.:3615  
 Max.   :46.60   Max.   :8.000   Max.   :455.0   Max.   :230.0   Max.   :5140  
                                                                               
  acceleration        year           origin                      name    
 Min.   : 8.00   Min.   :70.00   Min.   :1.000   amc matador       :  5  
 1st Qu.:13.78   1st Qu.:73.00   1st Qu.:1.000   ford pinto        :  5  
 Median :15.50   Median :76.00   Median :1.000   toyota corolla    :  5  
 Mean   :15.54   Mean   :75.98   Mean   :1.577   amc gremlin       :  4  
 3rd Qu.:17.02   3rd Qu.:79.00   3rd Qu.:2.000   amc hornet        :  4  
 Max.   :24.80   Max.   :82.00   Max.   :3.000   chevrolet chevette:  4  
                                                 (Other)           :365  </pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="application/vnd.jupyter.stderr">
<pre>The following objects are masked from car (pos = 4):

    acceleration, cylinders, displacement, horsepower, mpg, name,
    origin, weight, year

</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="n">car</span> <span class="o">=</span> <span class="nf">na.omit</span><span class="p">(</span><span class="n">car</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="c1">#  9.(a). Produce a scatterplot matrix which includes all of the variables in the data set.</span>
<span class="c1">#   </span>
<span class="c1">#  </span>

<span class="nf">pairs</span><span class="p">(</span><span class="n">car</span><span class="p">,</span><span class="n">panel</span><span class="o">=</span><span class="n">panel.smooth</span><span class="p">,</span><span class="n">main</span><span class="o">=</span><span class="s">&quot;scatter plots of all pairs of variables&quot;</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
iQX4H3w6Mteg2aVIAAAAAElFTkSuQmCC"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[5]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="c1">#  9.(b). Compute the matrix of correlations between the variables using the function cor().</span>
<span class="c1">#   </span>
<span class="c1">#   </span>

<span class="nf">library</span><span class="p">(</span><span class="n">dplyr</span><span class="p">)</span>
<span class="nf">cor</span><span class="p">(</span><span class="nf">select</span><span class="p">(</span><span class="n">car</span><span class="p">,</span> <span class="n">mpg</span><span class="p">,</span> <span class="n">weight</span><span class="p">,</span> <span class="n">displacement</span><span class="p">,</span> <span class="n">cylinders</span><span class="p">,</span> <span class="n">horsepower</span><span class="p">,</span> <span class="n">acceleration</span><span class="p">,</span> <span class="n">year</span><span class="p">,</span> <span class="n">origin</span> <span class="p">))</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="application/vnd.jupyter.stderr">
<pre>Warning message:
&#34;package &#39;dplyr&#39; was built under R version 3.6.3&#34;
Attaching package: &#39;dplyr&#39;

The following objects are masked from &#39;package:stats&#39;:

    filter, lag

The following objects are masked from &#39;package:base&#39;:

    intersect, setdiff, setequal, union

</pre>
</div>
</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<table>
<thead><tr><th></th><th scope=col>mpg</th><th scope=col>weight</th><th scope=col>displacement</th><th scope=col>cylinders</th><th scope=col>horsepower</th><th scope=col>acceleration</th><th scope=col>year</th><th scope=col>origin</th></tr></thead>
<tbody>
	<tr><th scope=row>mpg</th><td> 1.0000000</td><td>-0.8322442</td><td>-0.8051269</td><td>-0.7776175</td><td>-0.7784268</td><td> 0.4233285</td><td> 0.5805410</td><td> 0.5652088</td></tr>
	<tr><th scope=row>weight</th><td>-0.8322442</td><td> 1.0000000</td><td> 0.9329944</td><td> 0.8975273</td><td> 0.8645377</td><td>-0.4168392</td><td>-0.3091199</td><td>-0.5850054</td></tr>
	<tr><th scope=row>displacement</th><td>-0.8051269</td><td> 0.9329944</td><td> 1.0000000</td><td> 0.9508233</td><td> 0.8972570</td><td>-0.5438005</td><td>-0.3698552</td><td>-0.6145351</td></tr>
	<tr><th scope=row>cylinders</th><td>-0.7776175</td><td> 0.8975273</td><td> 0.9508233</td><td> 1.0000000</td><td> 0.8429834</td><td>-0.5046834</td><td>-0.3456474</td><td>-0.5689316</td></tr>
	<tr><th scope=row>horsepower</th><td>-0.7784268</td><td> 0.8645377</td><td> 0.8972570</td><td> 0.8429834</td><td> 1.0000000</td><td>-0.6891955</td><td>-0.4163615</td><td>-0.4551715</td></tr>
	<tr><th scope=row>acceleration</th><td> 0.4233285</td><td>-0.4168392</td><td>-0.5438005</td><td>-0.5046834</td><td>-0.6891955</td><td> 1.0000000</td><td> 0.2903161</td><td> 0.2127458</td></tr>
	<tr><th scope=row>year</th><td> 0.5805410</td><td>-0.3091199</td><td>-0.3698552</td><td>-0.3456474</td><td>-0.4163615</td><td> 0.2903161</td><td> 1.0000000</td><td> 0.1815277</td></tr>
	<tr><th scope=row>origin</th><td> 0.5652088</td><td>-0.5850054</td><td>-0.6145351</td><td>-0.5689316</td><td>-0.4551715</td><td> 0.2127458</td><td> 0.1815277</td><td> 1.0000000</td></tr>
</tbody>
</table>

</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[11]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="c1">#  9. (c). Use the lm() function to perform a multiple linear regression with mpg as the response and</span>
<span class="c1">#  all other variables except name as the predictors.</span>
<span class="c1">#  </span>
<span class="c1">#   </span>
<span class="n">lmcar</span> <span class="o">=</span> <span class="nf">lm</span><span class="p">(</span><span class="n">mpg</span> <span class="o">~</span> <span class="n">weight</span> <span class="o">+</span> <span class="n">displacement</span> <span class="o">+</span> <span class="n">cylinders</span> <span class="o">+</span> <span class="n">horsepower</span> <span class="o">+</span> <span class="n">acceleration</span> <span class="o">+</span> <span class="n">year</span> <span class="o">+</span> <span class="n">origin</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">car</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">lmcar</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>
Call:
lm(formula = mpg ~ weight + displacement + cylinders + horsepower + 
    acceleration + year + origin, data = car)

Residuals:
    Min      1Q  Median      3Q     Max 
-9.5903 -2.1565 -0.1169  1.8690 13.0604 

Coefficients:
               Estimate Std. Error t value Pr(&gt;|t|)    
(Intercept)  -17.218435   4.644294  -3.707  0.00024 ***
weight        -0.006474   0.000652  -9.929  &lt; 2e-16 ***
displacement   0.019896   0.007515   2.647  0.00844 ** 
cylinders     -0.493376   0.323282  -1.526  0.12780    
horsepower    -0.016951   0.013787  -1.230  0.21963    
acceleration   0.080576   0.098845   0.815  0.41548    
year           0.750773   0.050973  14.729  &lt; 2e-16 ***
origin         1.426141   0.278136   5.127 4.67e-07 ***
---
Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1

Residual standard error: 3.328 on 384 degrees of freedom
Multiple R-squared:  0.8215,	Adjusted R-squared:  0.8182 
F-statistic: 252.4 on 7 and 384 DF,  p-value: &lt; 2.2e-16
</pre>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><em>i. Is there a relationship between the predictors and the response?</em></p>
<p style="color:blue;">Yes, we see a very low p-value for the F-statistic so we can reject H0 that Bi = 0.   </p><p><em>ii. Which predictors appear to have a statistically significant relationship to the response?</em></p>
<p style="color:blue;">Weight, displacement, year and origin have a significant relationship to mpg as noted by the low p-values for each variable</p><p><em>iii. What does the coefficient for the year variable suggest?</em></p>
<p style="color:blue;">In this dataset, I would treat the year should be treated as a factor. Its qualitative, not quantitive. That said, its  regression coefficient of 0.7507727, suggests that for every one year, mpg increases by the coefficient. In other words, cars become more fuel efficient every year by almost 1 mpg / year. </p>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[13]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># 9. (d) Use the plot() function to produce diagnostic plots of the linear regression fit.</span>
<span class="c1">#</span>
<span class="c1">#</span>
<span class="nf">par</span><span class="p">(</span><span class="n">mfrow</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">2</span><span class="p">,</span> <span class="m">2</span><span class="p">))</span>
<span class="nf">plot</span><span class="p">(</span><span class="n">lmcar</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Comment on any problems you see with the fit.  Do the residual plots suggest any unusually large outliers? 
The Residual plot and the Standardized Residual plot both show a so-so linear fit though not a great one.  At 30 and beyond a right-tailed skewness can be seen.  The QQ plot confirms the fat right-tailed skewness beyond the 2nd positive quartile.</p>
<p>Does the leverage plot identify any observations with unusually high leverage?
The leverage plot identifies observation 14 as potentially having significant leverage through it isn't beyond the Cook's distance line.</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[7]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="c1">#  9.(e) Use the * and : symbols to fit linear regression models with interaction effects.</span>
<span class="c1">#   Do any interactions appear to be statistically significant?</span>
<span class="c1">#   </span>
<span class="c1"># </span>
<span class="n">lm.mult.car</span> <span class="o">=</span> <span class="nf">lm</span><span class="p">(</span><span class="n">mpg</span> <span class="o">~</span> <span class="p">(</span><span class="n">cylinders</span> <span class="o">+</span> <span class="n">displacement</span> <span class="o">+</span> <span class="n">horsepower</span><span class="p">)</span><span class="o">^</span><span class="m">2</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">car</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">lm.mult.car</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>
Call:
lm(formula = mpg ~ (cylinders + displacement + horsepower)^2, 
    data = car)

Residuals:
     Min       1Q   Median       3Q      Max 
-11.1907  -2.1959  -0.4285   1.9799  18.2020 

Coefficients:
                          Estimate Std. Error t value Pr(&gt;|t|)    
(Intercept)             55.6718928  4.8692360  11.433  &lt; 2e-16 ***
cylinders               -0.3603737  1.4593424  -0.247 0.805084    
displacement            -0.1156195  0.0263010  -4.396 1.43e-05 ***
horsepower              -0.2509992  0.0550410  -4.560 6.88e-06 ***
cylinders:displacement   0.0025919  0.0031956   0.811 0.417818    
cylinders:horsepower     0.0048743  0.0126823   0.384 0.700937    
displacement:horsepower  0.0005099  0.0001420   3.590 0.000374 ***
---
Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1

Residual standard error: 3.935 on 385 degrees of freedom
Multiple R-squared:  0.7498,	Adjusted R-squared:  0.7459 
F-statistic: 192.3 on 6 and 385 DF,  p-value: &lt; 2.2e-16
</pre>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><em>Commentary:</em>  As independent variables cylynders doesn't have a linear relationship with mpg. Displacement and horsepower individually show a statistical significance of influence on MPG.  The interaction terms cylinders:displacement and cylinders:horsepower are not statistcally significant.  displacement:horsepower interaction variable show a statistical significance in influence on MPG.</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[8]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="c1">#  9. (f) Try a few different transformations of the variables, such as log(X), √ X, X2.</span>
<span class="c1">#  Comment on your findings</span>
<span class="c1">#  </span>
<span class="c1">#  </span>


<span class="n">lm.car.logwt</span> <span class="o">=</span> <span class="nf">lm</span><span class="p">(</span><span class="n">mpg</span> <span class="o">~</span> <span class="nf">log</span><span class="p">(</span><span class="n">weight</span><span class="p">)</span> <span class="o">+</span> <span class="n">displacement</span> <span class="o">+</span> <span class="n">cylinders</span> <span class="o">+</span> <span class="n">horsepower</span> <span class="o">+</span> <span class="n">acceleration</span> <span class="o">+</span> <span class="n">year</span> <span class="o">+</span> <span class="n">origin</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">car</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">lm.car.logwt</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>
Call:
lm(formula = mpg ~ log(weight) + displacement + cylinders + horsepower + 
    acceleration + year + origin, data = car)

Residuals:
   Min     1Q Median     3Q    Max 
-9.382 -1.973 -0.016  1.681 12.803 

Coefficients:
               Estimate Std. Error t value Pr(&gt;|t|)    
(Intercept)  133.138912  11.531157  11.546  &lt; 2e-16 ***
log(weight)  -21.858785   1.651400 -13.237  &lt; 2e-16 ***
displacement   0.020977   0.006825   3.074 0.002265 ** 
cylinders     -0.432749   0.299977  -1.443 0.149946    
horsepower    -0.010072   0.012546  -0.803 0.422593    
acceleration   0.135179   0.089798   1.505 0.133051    
year           0.788784   0.047596  16.573  &lt; 2e-16 ***
origin         1.011407   0.262262   3.856 0.000135 ***
---
Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1

Residual standard error: 3.091 on 384 degrees of freedom
Multiple R-squared:  0.8459,	Adjusted R-squared:  0.8431 
F-statistic: 301.2 on 7 and 384 DF,  p-value: &lt; 2.2e-16
</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[9]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="nf">par</span><span class="p">(</span><span class="n">mfrow</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">2</span><span class="p">,</span> <span class="m">2</span><span class="p">))</span>
<span class="nf">plot</span><span class="p">(</span><span class="n">lm.car.logwt</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[13]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="nf">anova</span><span class="p">(</span><span class="n">lmcar</span><span class="p">,</span><span class="n">lm.car.logwt</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<table>
<thead><tr><th scope=col>Res.Df</th><th scope=col>RSS</th><th scope=col>Df</th><th scope=col>Sum of Sq</th><th scope=col>F</th><th scope=col>Pr(&gt;F)</th></tr></thead>
<tbody>
	<tr><td>384     </td><td>4252.213</td><td>NA      </td><td>      NA</td><td>NA      </td><td>NA      </td></tr>
	<tr><td>384     </td><td>3669.557</td><td> 0      </td><td>582.6551</td><td>NA      </td><td>NA      </td></tr>
</tbody>
</table>

</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><em>Comments on taking log(weight)</em>  <p style="color:blue;">The linear regression model is stronger by taking the log of the variable weight.  The R2 without the transformation is 82 and the R2 improved to 85 with the log transformation.  The diagnostic plots did not show much improvement.  Using anova to test which model is better shows that the log transformation of weight produces a better model. </p></p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[17]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="n">lm.car.sqd</span> <span class="o">=</span> <span class="nf">lm</span><span class="p">(</span><span class="n">mpg</span> <span class="o">~</span> <span class="nf">log</span><span class="p">(</span><span class="n">weight</span><span class="p">)</span> <span class="o">+</span> <span class="nf">I</span><span class="p">(</span><span class="n">displacement</span><span class="o">^</span><span class="m">2</span><span class="p">)</span> <span class="o">+</span> <span class="nf">I</span><span class="p">(</span><span class="n">cylinders</span><span class="o">^</span><span class="m">2</span><span class="p">)</span> <span class="o">+</span> <span class="n">horsepower</span> <span class="o">+</span> <span class="n">acceleration</span> <span class="o">+</span> <span class="n">year</span> <span class="o">+</span> <span class="n">origin</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">car</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">lm.car.sqd</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>
Call:
lm(formula = mpg ~ log(weight) + I(displacement^2) + I(cylinders^2) + 
    horsepower + acceleration + year + origin, data = car)

Residuals:
   Min     1Q Median     3Q    Max 
-9.380 -1.818  0.005  1.778 12.490 

Coefficients:
                    Estimate Std. Error t value Pr(&gt;|t|)    
(Intercept)        1.261e+02  1.062e+01  11.873  &lt; 2e-16 ***
log(weight)       -2.065e+01  1.494e+00 -13.825  &lt; 2e-16 ***
I(displacement^2)  5.052e-05  1.029e-05   4.911 1.35e-06 ***
I(cylinders^2)    -3.395e-02  2.170e-02  -1.565 0.118459    
horsepower        -2.814e-02  1.314e-02  -2.142 0.032847 *  
acceleration       1.037e-01  8.796e-02   1.179 0.239138    
year               7.922e-01  4.659e-02  17.004  &lt; 2e-16 ***
origin             9.459e-01  2.475e-01   3.822 0.000154 ***
---
Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1

Residual standard error: 3.031 on 384 degrees of freedom
Multiple R-squared:  0.8519,	Adjusted R-squared:  0.8492 
F-statistic: 315.5 on 7 and 384 DF,  p-value: &lt; 2.2e-16
</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[1]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="nf">par</span><span class="p">(</span><span class="n">mfrow</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">2</span><span class="p">,</span> <span class="m">2</span><span class="p">))</span>
<span class="nf">plot</span><span class="p">(</span><span class="n">lm.car.sqd</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="application/vnd.jupyter.stderr">
<pre>
Error in plot(lm.car.sqd): object &#39;lm.car.sqd&#39; not found
Traceback:

1. plot(lm.car.sqd)</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[19]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="nf">anova</span><span class="p">(</span><span class="n">lm.car.sqd</span><span class="p">,</span><span class="n">lm.car.logwt</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<table>
<thead><tr><th scope=col>Res.Df</th><th scope=col>RSS</th><th scope=col>Df</th><th scope=col>Sum of Sq</th><th scope=col>F</th><th scope=col>Pr(&gt;F)</th></tr></thead>
<tbody>
	<tr><td>384      </td><td>3528.448 </td><td>NA       </td><td>       NA</td><td>NA       </td><td>NA       </td></tr>
	<tr><td>384      </td><td>3669.557 </td><td> 0       </td><td>-141.1092</td><td>NA       </td><td>NA       </td></tr>
</tbody>
</table>

</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><em>Comments on taking squaring displacement and cyliners)</em> <p style="color:blue;"> The hope of squaring displacement and cylinders is to get rid of the negative correlation numbers as compared to MPG.  It didn't improve the linear regression model which is as strong as just taking the log(weight).  The R2 is the same and the Diagnostic plots do not improve by squaring displacement and cylinders.  Using anova to test which model is better shows that the log transformation of weight alone produces a better model. </p></p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[1]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="nf">library</span><span class="p">(</span><span class="n">ISLR</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[2]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="n">carseats</span> <span class="o">=</span> <span class="nf">as.data.frame</span><span class="p">(</span><span class="n">Carseats</span><span class="p">)</span>
<span class="nf">dim</span><span class="p">(</span><span class="n">carseats</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">carseats</span><span class="p">)</span>
<span class="nf">head</span><span class="p">(</span><span class="n">carseats</span><span class="p">)</span>
<span class="nf">attach</span><span class="p">(</span><span class="n">carseats</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<ol class=list-inline>
	<li>400</li>
	<li>11</li>
</ol>

</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>     Sales          CompPrice       Income        Advertising    
 Min.   : 0.000   Min.   : 77   Min.   : 21.00   Min.   : 0.000  
 1st Qu.: 5.390   1st Qu.:115   1st Qu.: 42.75   1st Qu.: 0.000  
 Median : 7.490   Median :125   Median : 69.00   Median : 5.000  
 Mean   : 7.496   Mean   :125   Mean   : 68.66   Mean   : 6.635  
 3rd Qu.: 9.320   3rd Qu.:135   3rd Qu.: 91.00   3rd Qu.:12.000  
 Max.   :16.270   Max.   :175   Max.   :120.00   Max.   :29.000  
   Population        Price        ShelveLoc        Age          Education   
 Min.   : 10.0   Min.   : 24.0   Bad   : 96   Min.   :25.00   Min.   :10.0  
 1st Qu.:139.0   1st Qu.:100.0   Good  : 85   1st Qu.:39.75   1st Qu.:12.0  
 Median :272.0   Median :117.0   Medium:219   Median :54.50   Median :14.0  
 Mean   :264.8   Mean   :115.8                Mean   :53.32   Mean   :13.9  
 3rd Qu.:398.5   3rd Qu.:131.0                3rd Qu.:66.00   3rd Qu.:16.0  
 Max.   :509.0   Max.   :191.0                Max.   :80.00   Max.   :18.0  
 Urban       US     
 No :118   No :142  
 Yes:282   Yes:258  
                    
                    
                    
                    </pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<table>
<thead><tr><th scope=col>Sales</th><th scope=col>CompPrice</th><th scope=col>Income</th><th scope=col>Advertising</th><th scope=col>Population</th><th scope=col>Price</th><th scope=col>ShelveLoc</th><th scope=col>Age</th><th scope=col>Education</th><th scope=col>Urban</th><th scope=col>US</th></tr></thead>
<tbody>
	<tr><td> 9.50 </td><td>138   </td><td> 73   </td><td>11    </td><td>276   </td><td>120   </td><td>Bad   </td><td>42    </td><td>17    </td><td>Yes   </td><td>Yes   </td></tr>
	<tr><td>11.22 </td><td>111   </td><td> 48   </td><td>16    </td><td>260   </td><td> 83   </td><td>Good  </td><td>65    </td><td>10    </td><td>Yes   </td><td>Yes   </td></tr>
	<tr><td>10.06 </td><td>113   </td><td> 35   </td><td>10    </td><td>269   </td><td> 80   </td><td>Medium</td><td>59    </td><td>12    </td><td>Yes   </td><td>Yes   </td></tr>
	<tr><td> 7.40 </td><td>117   </td><td>100   </td><td> 4    </td><td>466   </td><td> 97   </td><td>Medium</td><td>55    </td><td>14    </td><td>Yes   </td><td>Yes   </td></tr>
	<tr><td> 4.15 </td><td>141   </td><td> 64   </td><td> 3    </td><td>340   </td><td>128   </td><td>Bad   </td><td>38    </td><td>13    </td><td>Yes   </td><td>No    </td></tr>
	<tr><td>10.81 </td><td>124   </td><td>113   </td><td>13    </td><td>501   </td><td> 72   </td><td>Bad   </td><td>78    </td><td>16    </td><td>No    </td><td>Yes   </td></tr>
</tbody>
</table>

</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
</ol>
<p>(a) Fit a multiple regression model to predict Sales using Price, Urban, and US.</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[3]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="n">lm.sales</span> <span class="o">=</span> <span class="nf">lm</span><span class="p">(</span><span class="n">Sales</span> <span class="o">~</span> <span class="n">Price</span> <span class="o">+</span> <span class="n">Urban</span> <span class="o">+</span> <span class="n">US</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">carseats</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">lm.sales</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>
Call:
lm(formula = Sales ~ Price + Urban + US, data = carseats)

Residuals:
    Min      1Q  Median      3Q     Max 
-6.9206 -1.6220 -0.0564  1.5786  7.0581 

Coefficients:
             Estimate Std. Error t value Pr(&gt;|t|)    
(Intercept) 13.043469   0.651012  20.036  &lt; 2e-16 ***
Price       -0.054459   0.005242 -10.389  &lt; 2e-16 ***
UrbanYes    -0.021916   0.271650  -0.081    0.936    
USYes        1.200573   0.259042   4.635 4.86e-06 ***
---
Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1

Residual standard error: 2.472 on 396 degrees of freedom
Multiple R-squared:  0.2393,	Adjusted R-squared:  0.2335 
F-statistic: 41.52 on 3 and 396 DF,  p-value: &lt; 2.2e-16
</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="nf">contrasts</span><span class="p">(</span><span class="n">Urban</span><span class="p">)</span>
<span class="nf">contrasts</span><span class="p">(</span><span class="n">US</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<table>
<thead><tr><th></th><th scope=col>Yes</th></tr></thead>
<tbody>
	<tr><th scope=row>No</th><td>0</td></tr>
	<tr><th scope=row>Yes</th><td>1</td></tr>
</tbody>
</table>

</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<table>
<thead><tr><th></th><th scope=col>Yes</th></tr></thead>
<tbody>
	<tr><th scope=row>No</th><td>0</td></tr>
	<tr><th scope=row>Yes</th><td>1</td></tr>
</tbody>
</table>

</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li>(b) Provide an interpretation of each coefficient in the model. Be careful—some of the variables in the model are qualitative!   </li>
</ol>
<p style="color:blue;">The model suggests that Sales is impacted by price and whether the buy is in the US or not. </p><p>Specifically</p>
<p style="color:blue;">Price - there is a relationship betweeen sales and price which means as price goes up, the sales figure goes down.</p><p style="color:blue;">Urban  - due to the high p-value, there isn't enough information to reject the H0 that influence of Urban is 0.</p><p style="color:blue;">US  - the regression shows that there is a relationship between Sales and whether or not the store is in the US as the p-value of this varible is significant.</p><p style="color:blue;">Sales equation is</p><div style="border:3px double blue;padding:2%;">

Sales = 13.04 - 0.5BPrice - .02Urban_yes + 1.2US_yes
</div>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li>(c) Write out the model in equation form, being careful to handle the qualitative variables properly</li>
</ol>
<p style="color:blue;">yi = B0 + B1 + *E*                if the observation is not urban & is not in US</p>    
    <p style="color:blue;">yi = B0 + B1 + B2 + *E*           if the observation is urban & is not in US</p>         
    <p style="color:blue;">yi = B0 + B1 + B3 + *E*           if the observation is not urban & is in US</p>    
    <p style="color:blue;">yi = B0 + B1 + B2 + +B3+  *E*     if the observation is urban & is in US</p>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li><p>(d) For which of the predictors can you reject the null hypothesis H0 : βj = 0?</p>
<p style="color:blue;">I can reject the H0 for UrbanYes as the p-value is very high</p></li>
</ol>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[20]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="c1">#  (e) On the basis of your response to the previous question, fit a </span>
<span class="c1">#  smaller model that  only uses the predictors for which there</span>
<span class="c1"># is evidence of association with the outcome.</span>


<span class="n">lm.sales2</span> <span class="o">=</span> <span class="nf">lm</span><span class="p">(</span><span class="n">Sales</span> <span class="o">~</span> <span class="n">Price</span> <span class="o">+</span> <span class="n">US</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">carseats</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">lm.sales2</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>
Call:
lm(formula = Sales ~ Price + US, data = carseats)

Residuals:
    Min      1Q  Median      3Q     Max 
-6.9269 -1.6286 -0.0574  1.5766  7.0515 

Coefficients:
            Estimate Std. Error t value Pr(&gt;|t|)    
(Intercept) 13.03079    0.63098  20.652  &lt; 2e-16 ***
Price       -0.05448    0.00523 -10.416  &lt; 2e-16 ***
USYes        1.19964    0.25846   4.641 4.71e-06 ***
---
Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1

Residual standard error: 2.469 on 397 degrees of freedom
Multiple R-squared:  0.2393,	Adjusted R-squared:  0.2354 
F-statistic: 62.43 on 2 and 397 DF,  p-value: &lt; 2.2e-16
</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[21]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="nf">anova</span><span class="p">(</span><span class="n">lm.sales</span><span class="p">,</span> <span class="n">lm.sales2</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<table>
<thead><tr><th scope=col>Res.Df</th><th scope=col>RSS</th><th scope=col>Df</th><th scope=col>Sum of Sq</th><th scope=col>F</th><th scope=col>Pr(&gt;F)</th></tr></thead>
<tbody>
	<tr><td>396        </td><td>2420.835   </td><td>NA         </td><td>         NA</td><td>        NA </td><td>       NA  </td></tr>
	<tr><td>397        </td><td>2420.874   </td><td>-1         </td><td>-0.03979039</td><td>0.00650891 </td><td>0.9357389  </td></tr>
</tbody>
</table>

</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li>(f) How well do the models in (a) and (e) fit the data?   </li>
</ol>
<p style="color:blue;">According to the RSE and the R2 values the models have similar fits but at 24% neither models explaing the variance in sales.  Comparing the models using the anova command finds that the smaller model is the strongest fit for the data.</p>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[22]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="c1">#10. (g) Using the model from (e), obtain 95% confidence intervals for the coefficient(s).</span>
<span class="c1">#</span>
<span class="c1">#</span>
<span class="nf">confint</span><span class="p">(</span><span class="n">lm.sales2</span><span class="p">,</span> <span class="n">level</span> <span class="o">=</span> <span class="m">0.95</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<table>
<thead><tr><th></th><th scope=col>2.5 %</th><th scope=col>97.5 %</th></tr></thead>
<tbody>
	<tr><th scope=row>(Intercept)</th><td>11.79032020</td><td>14.27126531</td></tr>
	<tr><th scope=row>Price</th><td>-0.06475984</td><td>-0.04419543</td></tr>
	<tr><th scope=row>USYes</th><td> 0.69151957</td><td> 1.70776632</td></tr>
</tbody>
</table>

</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[23]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="c1">#  (h) Is there evidence of outliers or high leverage observations </span>
<span class="c1">#      in the model from (e)?</span>
<span class="c1">#</span>
<span class="c1">#</span>
<span class="c1">#cooksd</span>
<span class="n">cooksd</span> <span class="o">=</span> <span class="nf">cooks.distance</span><span class="p">(</span><span class="n">lm.sales2</span><span class="p">)</span>

<span class="c1"># # plot cook&#39;s distance</span>
<span class="nf">plot</span><span class="p">(</span><span class="n">cooksd</span><span class="p">,</span> <span class="n">pch</span><span class="o">=</span><span class="s">&quot;*&quot;</span><span class="p">,</span> <span class="n">cex</span><span class="o">=</span><span class="m">2</span><span class="p">,</span> <span class="n">main</span><span class="o">=</span><span class="s">&quot;Influential Obs by Cooks distance&quot;</span><span class="p">)</span>  
<span class="c1"># # add cutoff line</span>
<span class="nf">abline</span><span class="p">(</span><span class="n">h</span> <span class="o">=</span> <span class="m">4</span><span class="o">*</span><span class="nf">mean</span><span class="p">(</span><span class="n">cooksd</span><span class="p">,</span> <span class="n">na.rm</span><span class="o">=</span><span class="bp">T</span><span class="p">),</span> <span class="n">col</span><span class="o">=</span><span class="s">&quot;red&quot;</span><span class="p">)</span>  
<span class="c1"># # add labels</span>
<span class="nf">text</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="m">1</span><span class="o">:</span><span class="nf">length</span><span class="p">(</span><span class="n">cooksd</span><span class="p">)</span><span class="m">+1</span><span class="p">,</span> <span class="n">y</span><span class="o">=</span><span class="n">cooksd</span><span class="p">,</span> <span class="n">labels</span> <span class="o">=</span> 
     <span class="nf">ifelse</span><span class="p">(</span><span class="n">cooksd</span><span class="o">&gt;</span><span class="m">4</span><span class="o">*</span><span class="nf">mean</span><span class="p">(</span><span class="n">cooksd</span><span class="p">,</span> <span class="n">na.rm</span><span class="o">=</span><span class="bp">T</span><span class="p">),</span> <span class="nf">names</span><span class="p">(</span><span class="n">cooksd</span><span class="p">),</span><span class="s">&quot;&quot;</span><span class="p">),</span> <span class="n">col</span><span class="o">=</span><span class="s">&quot;red&quot;</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
rkJggg=="
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p style="color:blue;">According to the Cook's distance plot, there are about 20 outliers that may unduly influence the linear regression line.</p>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
</ol>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li>(a) Recall that the coefficient estimate ˆ β for the linear regression of
Y onto X without an intercept is given by (3.38). Under what
circumstance is the coefficient estimate for the regression of X
onto Y the same as the coefficient estimate for the regression of
Y onto X?</li>
</ol>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p style="color:blue;">sum of squares of observed x-values = sum of squares of observed y values</p>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li>(b) Generate an example in R with n = 100 observations in which the coefficient estimate for the regression of X onto Y is different from the coefficient estimate for the regression of Y onto X. </li>
</ol>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[15]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="nf">set.seed</span><span class="p">(</span><span class="m">1</span><span class="p">)</span>
<span class="n">x</span><span class="o">&lt;-</span><span class="nf">rnorm</span><span class="p">(</span><span class="m">100</span><span class="p">)</span>
<span class="n">y</span><span class="o">&lt;-</span><span class="m">2</span><span class="o">*</span><span class="n">x</span>
<span class="n">ln.12b1</span> <span class="o">=</span> <span class="nf">lm</span><span class="p">(</span><span class="n">y</span><span class="o">~</span><span class="n">x</span><span class="m">+0</span><span class="p">)</span>
<span class="n">ln.12b2</span> <span class="o">=</span> <span class="nf">lm</span><span class="p">(</span><span class="n">x</span><span class="o">~</span><span class="n">y</span><span class="m">+0</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">ln.12b1</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">ln.12b2</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="application/vnd.jupyter.stderr">
<pre>Warning message in summary.lm(ln.12b1):
&#34;essentially perfect fit: summary may be unreliable&#34;</pre>
</div>
</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>
Call:
lm(formula = y ~ x + 0)

Residuals:
       Min         1Q     Median         3Q        Max 
-3.450e-16 -3.010e-17  4.600e-18  6.760e-17  7.637e-15 

Coefficients:
   Estimate Std. Error   t value Pr(&gt;|t|)    
x 2.000e+00  8.611e-17 2.323e+16   &lt;2e-16 ***
---
Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1

Residual standard error: 7.753e-16 on 99 degrees of freedom
Multiple R-squared:      1,	Adjusted R-squared:      1 
F-statistic: 5.394e+32 on 1 and 99 DF,  p-value: &lt; 2.2e-16
</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="application/vnd.jupyter.stderr">
<pre>Warning message in summary.lm(ln.12b2):
&#34;essentially perfect fit: summary may be unreliable&#34;</pre>
</div>
</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>
Call:
lm(formula = x ~ y + 0)

Residuals:
       Min         1Q     Median         3Q        Max 
-1.725e-16 -1.510e-17  2.300e-18  3.380e-17  3.818e-15 

Coefficients:
   Estimate Std. Error   t value Pr(&gt;|t|)    
y 5.000e-01  2.153e-17 2.323e+16   &lt;2e-16 ***
---
Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1

Residual standard error: 3.876e-16 on 99 degrees of freedom
Multiple R-squared:      1,	Adjusted R-squared:      1 
F-statistic: 5.394e+32 on 1 and 99 DF,  p-value: &lt; 2.2e-16
</pre>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li>(c) Generate an example in R with n = 100 observations in which the coefficient estimate for the regression of X onto Y is the same as the coefficient estimate for the regression of Y onto X. </li>
</ol>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[26]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-r"><pre><span></span><span class="n">x</span><span class="o">&lt;-</span><span class="m">100</span><span class="o">:</span><span class="m">1</span>

<span class="n">y</span> <span class="o">&lt;-</span> <span class="o">-</span><span class="nf">sample</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="m">100</span><span class="p">)</span>
<span class="n">x</span>
<span class="n">y</span>
<span class="nf">sum</span><span class="p">(</span><span class="n">x</span><span class="o">^</span><span class="m">2</span><span class="p">)</span>
<span class="nf">sum</span><span class="p">(</span><span class="n">y</span><span class="o">^</span><span class="m">2</span><span class="p">)</span>
<span class="n">ln.12c1</span> <span class="o">=</span> <span class="nf">lm</span><span class="p">(</span><span class="n">y</span><span class="o">~</span><span class="n">x</span><span class="m">+0</span><span class="p">)</span>
<span class="n">ln.12c2</span> <span class="o">=</span> <span class="nf">lm</span><span class="p">(</span><span class="n">x</span><span class="o">~</span><span class="n">y</span><span class="m">+0</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">ln.12c1</span><span class="p">)</span>
<span class="nf">summary</span><span class="p">(</span><span class="n">ln.12c2</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<ol class=list-inline>
	<li>100</li>
	<li>99</li>
	<li>98</li>
	<li>97</li>
	<li>96</li>
	<li>95</li>
	<li>94</li>
	<li>93</li>
	<li>92</li>
	<li>91</li>
	<li>90</li>
	<li>89</li>
	<li>88</li>
	<li>87</li>
	<li>86</li>
	<li>85</li>
	<li>84</li>
	<li>83</li>
	<li>82</li>
	<li>81</li>
	<li>80</li>
	<li>79</li>
	<li>78</li>
	<li>77</li>
	<li>76</li>
	<li>75</li>
	<li>74</li>
	<li>73</li>
	<li>72</li>
	<li>71</li>
	<li>70</li>
	<li>69</li>
	<li>68</li>
	<li>67</li>
	<li>66</li>
	<li>65</li>
	<li>64</li>
	<li>63</li>
	<li>62</li>
	<li>61</li>
	<li>60</li>
	<li>59</li>
	<li>58</li>
	<li>57</li>
	<li>56</li>
	<li>55</li>
	<li>54</li>
	<li>53</li>
	<li>52</li>
	<li>51</li>
	<li>50</li>
	<li>49</li>
	<li>48</li>
	<li>47</li>
	<li>46</li>
	<li>45</li>
	<li>44</li>
	<li>43</li>
	<li>42</li>
	<li>41</li>
	<li>40</li>
	<li>39</li>
	<li>38</li>
	<li>37</li>
	<li>36</li>
	<li>35</li>
	<li>34</li>
	<li>33</li>
	<li>32</li>
	<li>31</li>
	<li>30</li>
	<li>29</li>
	<li>28</li>
	<li>27</li>
	<li>26</li>
	<li>25</li>
	<li>24</li>
	<li>23</li>
	<li>22</li>
	<li>21</li>
	<li>20</li>
	<li>19</li>
	<li>18</li>
	<li>17</li>
	<li>16</li>
	<li>15</li>
	<li>14</li>
	<li>13</li>
	<li>12</li>
	<li>11</li>
	<li>10</li>
	<li>9</li>
	<li>8</li>
	<li>7</li>
	<li>6</li>
	<li>5</li>
	<li>4</li>
	<li>3</li>
	<li>2</li>
	<li>1</li>
</ol>

</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
<ol class=list-inline>
	<li>-72</li>
	<li>-32</li>
	<li>-3</li>
	<li>-89</li>
	<li>-19</li>
	<li>-67</li>
	<li>-54</li>
	<li>-39</li>
	<li>-88</li>
	<li>-62</li>
	<li>-97</li>
	<li>-31</li>
	<li>-51</li>
	<li>-53</li>
	<li>-21</li>
	<li>-79</li>
	<li>-75</li>
	<li>-61</li>
	<li>-14</li>
	<li>-87</li>
	<li>-95</li>
	<li>-47</li>
	<li>-29</li>
	<li>-77</li>
	<li>-34</li>
	<li>-64</li>
	<li>-20</li>
	<li>-74</li>
	<li>-98</li>
	<li>-1</li>
	<li>-40</li>
	<li>-2</li>
	<li>-42</li>
	<li>-70</li>
	<li>-23</li>
	<li>-18</li>
	<li>-24</li>
	<li>-30</li>
	<li>-91</li>
	<li>-9</li>
	<li>-41</li>
	<li>-59</li>
	<li>-15</li>
	<li>-8</li>
	<li>-10</li>
	<li>-13</li>
	<li>-82</li>
	<li>-83</li>
	<li>-80</li>
	<li>-55</li>
	<li>-78</li>
	<li>-17</li>
	<li>-86</li>
	<li>-38</li>
	<li>-33</li>
	<li>-7</li>
	<li>-96</li>
	<li>-16</li>
	<li>-100</li>
	<li>-58</li>
	<li>-12</li>
	<li>-60</li>
	<li>-43</li>
	<li>-68</li>
	<li>-37</li>
	<li>-45</li>
	<li>-26</li>
	<li>-44</li>
	<li>-36</li>
	<li>-22</li>
	<li>-93</li>
	<li>-4</li>
	<li>-90</li>
	<li>-85</li>
	<li>-73</li>
	<li>-49</li>
	<li>-63</li>
	<li>-71</li>
	<li>-76</li>
	<li>-94</li>
	<li>-35</li>
	<li>-6</li>
	<li>-50</li>
	<li>-57</li>
	<li>-84</li>
	<li>-11</li>
	<li>-52</li>
	<li>-92</li>
	<li>-99</li>
	<li>-25</li>
	<li>-56</li>
	<li>-27</li>
	<li>-5</li>
	<li>-46</li>
	<li>-65</li>
	<li>-69</li>
	<li>-48</li>
	<li>-81</li>
	<li>-66</li>
	<li>-28</li>
</ol>

</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
338350
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output " data-mime-type="text/html">
338350
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>
Call:
lm(formula = y ~ x + 0)

Residuals:
   Min     1Q Median     3Q    Max 
-90.05 -41.60 -15.30  16.32  70.09 

Coefficients:
  Estimate Std. Error t value Pr(&gt;|t|)    
x -0.74579    0.06695  -11.14   &lt;2e-16 ***
---
Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1

Residual standard error: 38.95 on 99 degrees of freedom
Multiple R-squared:  0.5562,	Adjusted R-squared:  0.5517 
F-statistic: 124.1 on 1 and 99 DF,  p-value: &lt; 2.2e-16
</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedText jp-OutputArea-output " data-mime-type="text/plain">
<pre>
Call:
lm(formula = x ~ y + 0)

Residuals:
   Min     1Q Median     3Q    Max 
-61.83 -14.32  14.70  44.83  95.76 

Coefficients:
  Estimate Std. Error t value Pr(&gt;|t|)    
y -0.74579    0.06695  -11.14   &lt;2e-16 ***
---
Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1

Residual standard error: 38.95 on 99 degrees of freedom
Multiple R-squared:  0.5562,	Adjusted R-squared:  0.5517 
F-statistic: 124.1 on 1 and 99 DF,  p-value: &lt; 2.2e-16
</pre>
</div>

</div>

</div>

</div>

</div>
</body>







</html>
