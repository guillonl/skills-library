---
name: Adapt
description: Adapt designs across screen sizes, devices, and platforms with breakpoints and fluid layouts
tags: [responsive, design, layout]
author: Superpowers
date: 2026-03-15
color: teal
---

Audit the current design for responsive behavior across five breakpoints: mobile (320-480px), tablet portrait (481-768px), tablet landscape (769-1024px), desktop (1025-1440px), and large screens (1441px+). Identify elements that break, overflow, or lose usability at each threshold.

Use fluid design techniques: clamp() for typography and spacing, min()/max() for container widths, and CSS Grid auto-fit/auto-fill for adaptive column layouts. Minimize hard breakpoints by designing fluid-first.

Adapt interaction patterns per device: swipe gestures on touch, hover states on pointer, keyboard navigation on desktop. Ensure touch targets are minimum 44x44px and interactive elements have adequate spacing to prevent accidental taps.

Test on real devices when possible, and use browser device emulation as a baseline. Validate that content reflow preserves reading order, navigation remains accessible, and no horizontal scrolling occurs at any viewport width.
