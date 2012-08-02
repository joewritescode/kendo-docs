---
title: Draggable Overview
slug: gs-web-draggable-overview
tags: getting-started,web
publish: true
---

# Draggable Overview

## Draggable

Enable draggable functionality on any DOM element.

## **Draggable** initialization

    var draggable = $("#draggable").kendoDraggable();

## DropTarget

Enable any DOM element to be a target for draggable elements.

## **DropTarget** initialization

    var dropTarget = $("#dropTarget").kendoDropTarget();

## DropTargetArea

Use a jQuery selector to enable DOM elements within an area to be targets for draggable elements.

## **DropTargetArea** initialization

    var dropTargetArea = $("#dropTargetArea").kendoDropTargetArea({ filter: ".dropTargets" });
