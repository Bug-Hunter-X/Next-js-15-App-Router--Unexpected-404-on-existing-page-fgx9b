# Next.js 15 App Router Unexpected 404 Error

This repository demonstrates a strange bug encountered in Next.js 15's App Router.  A page that clearly exists returns a 404 error when navigated to.  This is not a typical routing issue, it seems to be related to some unexpected interaction within the app directory structure.

## Bug Description

The `pages/index.js` file contains a simple component.  Despite this, navigating to `/` produces a 404 error.  The issue appears to be related to the App Router's internal behavior; the file exists and is correctly placed, yet it isn't recognized.

## Reproduction

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to `/` in your browser.  A 404 error will likely be shown.

## Solution

The solution may involve correctly configuring the application structure or addressing a potential conflict within the app directory setup. The root issue is related to the app router, possibly a misconfiguration.  This issue might be caused by a combination of factors, such as improper file naming or file paths, or conflicts with other app directory functionalities, or a bug in the Next.js 15 version being used.  The solution in the `solutionContent` is just a possible one, more investigation might be necessary for other variations of the problem.
