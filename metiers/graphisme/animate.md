---
name: Animate
description: Enhance features with purposeful animations, micro-interactions, and motion effects
tags: [animation, motion, design]
author: Superpowers
date: 2026-03-15
color: blue
---

Review the interface for static transitions that would benefit from motion. Focus on state changes (open/close, show/hide, enter/exit), feedback moments (button presses, form submissions), and spatial navigation (page transitions, drawer slides).

Apply the principle of meaningful motion: every animation must communicate something — direction, hierarchy, causality, or state. Avoid motion for decoration alone. Use easing curves that feel natural (ease-out for entrances, ease-in for exits).

Keep durations between 150-400ms for UI elements. Stagger related elements by 50-100ms for sequential reveals. Use CSS transitions for simple state changes and JavaScript animation libraries (Framer Motion, GSAP) for complex orchestration.

Always implement prefers-reduced-motion media query to disable or simplify animations for users who need it. Test on low-end devices to ensure animations maintain 60fps.
