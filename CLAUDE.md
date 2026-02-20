# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A single-page calculator web application built with vanilla HTML, CSS, and JavaScript. No build tools, frameworks, or dependencies.

## Architecture

- `calculator.html` — Self-contained calculator with embedded `<style>` and `<script>` sections
  - **CSS**: 3D neumorphic design using CSS gradients, box-shadows, and perspective transforms
  - **JS**: Simple state machine (`current`, `prev`, `operator`, `resetNext`) handling arithmetic operations with keyboard support

## Development

Open `calculator.html` directly in a browser — no server or build step required.

```
start calculator.html
```

## Communication

- 모든 결과값과 설명은 반드시 **한글**로 작성할 것.
