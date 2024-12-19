# Tailwind CSS Purge Configuration Issue

This repository demonstrates a common issue encountered when using Tailwind CSS with JavaScript frameworks such as Vue.js or React.js.  The problem is that necessary Tailwind CSS classes are purged, resulting in missing styles in the application. This is often caused by an improperly configured `purge` option in the `tailwind.config.js` file.

## Bug Report

The `bug.js` file shows how the Tailwind classes are used within a Vue/React component and how the styles fail to apply due to the purge configuration.

## Solution

The `bugSolution.js` file illustrates the corrected `tailwind.config.js` configuration, ensuring that the necessary classes are not purged and allowing the styles to be applied correctly. This demonstrates different methods of configuring the purge option for effective class inclusion.