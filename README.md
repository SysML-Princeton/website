# SAIL@Princeton

The official website of the Systems for Artificial Intelligence Lab @ Princeton!

## Adding a new person

- In `people.html`, add a new entry under "Students." Include the person's website URL, update the id in the `<h5>` tag, and upload a centered headshot (preferably a .jpg for easier management).
- In `index.html`, add their headshot under the relevant research directions. Update the `href`, `src`, and `alt` attributes in the `<a>` tag.
- Submit a PR for review!

## Adding a new publication

- In `publications.html`, add a new `<li class="paper-item">` entry. The easiest way to go with this is to copy the entire `<li>` block of an existing paper and update the information.
- Use `<span class="badge badge-secondary">` for keyword tags. Choose existing keywords so the paper appears under the right category on `index.html`.
- Update the paper's PDF URL.
- Add an abstract inside `<div class="card card-body">`. Ensure the Abstract button toggles correctly by updating the `href` in the button tag and the `id` in the card. Use `projectname-abstract` as the naming convention for the ID.
- Optionally, add a button linking to a project website, Hugging Face model page, etc.. Use `btn-outline-secondary` for unclickable, grey buttons.

- Submit a PR for review!

## Updating existing information (headshot, homepage link, etc.)

- Please simply submit a PR for review!

## Subscribing to the mailing list

Use this [link](https://lists.cs.princeton.edu/mailman3/lists/sail@lists.cs.princeton.edu/)!
