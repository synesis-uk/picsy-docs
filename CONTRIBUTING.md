# Contribute to the PICSy documentation

The docs should help a PICSy user complete a real task without needing to understand how the application is configured internally.

## Make a change

1. Create a branch from the latest default branch.
2. Run `npm install` if dependencies are not installed.
3. Run `npm run dev` and review the page in the local Mintlify preview.
4. Run `npm run check:links`.
5. Open a pull request and review the Mintlify preview deployment.

## Writing style

- Lead with the outcome the reader wants.
- Write directly to the reader using “you”.
- Keep the tone concise, clear and informal.
- Use sentence case for headings.
- Put interface labels in bold, such as **Catchment settings**.
- Use the exact label shown in PICSy.
- Prefer a short procedure to a long description of the interface.
- Explain an unfamiliar term when it first matters.

## Screenshots

- Prefer a 16:9 source capture, such as 1920×1080, then crop it for the page.
- Use another aspect ratio when it explains the interface better.
- Use the current PICSy interface and non-sensitive example data.
- Show enough of the screen to orient the reader.
- Add an image only when it makes a step easier to understand than text alone.
- Recheck screenshots when the documented workflow changes.

## Scope

The initial docs cover simple site use: adding a site, analysing it, configuring catchments, projections and comparisons, map settings, exports, Benchmarking, Target Search and Directories.

Do not document organisation setup, workspace configuration, print-layout editing, bundles, internal scene configuration, admin tools or methodology unless the scope is explicitly expanded.
