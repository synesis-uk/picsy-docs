# PICSy documentation instructions

## Purpose and audience

Write for a generic PICSy user completing an everyday task. Do not assume a particular role, organisation structure or level of technical knowledge.

## Source of truth

- Treat the current PICSy application as the source of truth for behaviour and interface copy.
- Inspect the relevant application flow before documenting it.
- Use exact interface labels. Do not infer a label from old documentation.
- If behaviour differs by access, say so briefly without documenting entitlement internals.
- Do not copy content from the old beta documentation without rechecking it against the current app.

## Content scope

The current scope is:

- adding and opening a site
- using the site analysis workspace
- configuring catchment type and range
- editing catchment hexes and built-up-area inclusion
- keeping separate general and staffing catchments
- population projections and comparisons
- map styles and layers
- PDF and Excel export
- Benchmarking, Target Search and Directories

Leave out organisation and workspace configuration, print-layout editing, bundles, internal scene configuration, admin features and methodology unless the user expands the scope.

## Writing style

- Keep the tone concise, informal and matter-of-fact.
- Lead with the task or result.
- Address the reader as “you”.
- Use active voice and short sentences.
- Use sentence case for page titles and headings.
- Bold interface labels: select **Export**.
- Prefer task-based page titles such as “Configure a catchment”.
- Avoid promotional language, filler, generic introductions and unnecessary tips.
- Do not invent product behaviour, examples or permissions.

## Information architecture

- Keep one main user job per page.
- Organise pages by user goal, not by application component or code ownership.
- Prefer stable descriptions of a workflow over brittle instructions based only on screen position.
- Add links to the natural next step where they help the reader continue.
- Split a page when it becomes difficult to scan or contains more than one distinct procedure.

## Screenshots

- Prefer a 16:9 source capture, such as 1920×1080, when it gives enough room to show the workflow clearly.
- Crop the image for its final placement. Use another aspect ratio when that explains the interface better.
- Use current, non-sensitive data and avoid local development overlays.
- Do not add a screenshot when text is clearer or the interface is likely to change immediately.
- Give each image useful alt text and keep its purpose clear from the surrounding copy.

## Local workflow

- Pages are MDX files with YAML frontmatter.
- Navigation and site configuration live in `docs.json`.
- Run `npm run dev` for a local preview.
- Run `npm run check:links` before completing a content change.
- Review the rendered page, not only the MDX source.

## Definition of done

- The documented workflow has been checked against the current application.
- Interface labels match the application.
- Links and MDX render successfully.
- New pages appear in `docs.json` in a sensible order.
- Screenshots, when used, are current and sized for their purpose.
