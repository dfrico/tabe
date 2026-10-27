# Changelog

All notable changes to Tabe are listed here. The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Added
- Meals edited by hand are marked with a dot, and “New menu” can keep them and re-plan only the rest.
- Nutrition tab: weekly goals per food group, computed from each dish's ingredients.
- Ingredients tab: the shopping list for the planned meals, with ticks shared between phones.
- Dish roles (full meal, combinable, side only), seasons, lunch or dinner, and multi-meal dishes with leftovers.
- Second dish per meal.
- Dishes tab with lunch and dinner sections and sorting.
- Live sync between devices via server-sent events.
- Installable PWA with offline support over HTTPS.
- Raspberry Pi deployment with a systemd unit and push-to-deploy.
- HTTP API documented for agents (AGENTS.md).

### Changed
- Renamed from "menu" to Tabe.
- License changed from MIT to AGPL-3.0.

## [0.1.0] - 2025-01-06

### Added
- First version: a dish list in CSV and a constraint-solver menu planner (OR-Tools CP-SAT) with a web client.
