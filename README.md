[README.md](https://github.com/user-attachments/files/34311950/README.md)
# VIT FFCS Timetable Planner

A browser-based timetable planning tool built specifically for **VIT
students** following the Fully Flexible Credit System (FFCS).

The planner helps students organize theory and laboratory slots,
identify timetable clashes, manage alternative course combinations, and
keep course information in one place.

## Features

-   **VIT FFCS slot mapping** -- Maps theory and laboratory slot
    combinations to their corresponding periods in the weekly timetable.
-   **Automatic clash detection** -- Checks the VIT slot mapping and
    warns when a proposed course overlaps with an existing course.
-   **Theory--lab association** -- Link a laboratory course to its
    corresponding theory course.
-   **Multiple lab-session linking** -- Group related laboratory
    sessions under a parent lab course, with combined slot and venue
    details in the course registry.
-   **Course classification** -- Classify labs as standalone, linked to
    theory, or linked to another lab session.
-   **Course details** -- Maintain course name, optional course code,
    faculty, venue, credits, slot combination, and colour.
-   **Multiple timetable drafts** -- Create, rename, duplicate, switch
    between, and delete timetable drafts to explore different course
    combinations.
-   **Draft comparison** -- Compare saved drafts when planning
    alternative schedules.
-   **Undo and redo** -- Reverse or restore recent timetable changes.
-   **Weekend view** -- Toggle Saturday and Sunday in the timetable.
-   **Course registry** -- View registered courses and their details in
    a consolidated table.
-   **Credit calculation** -- Calculates total credits without counting
    linked child sessions again.
-   **Dark and light themes** -- Switch the interface theme.
-   **PNG export** -- Export the timetable as an image.

## Tech Stack

-   HTML5
-   CSS3
-   JavaScript
-   Tailwind CSS
-   Font Awesome
-   Google Fonts -- Inter
-   html2canvas

## Getting Started

### Run locally

1.  Clone this repository:

    ``` bash
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
    ```

2.  Open the project folder.

3.  Open `index.html` in a modern web browser.

If your HTML file is currently named `ffcs_v3(1).html`, you can rename
it to `index.html` before uploading it to GitHub. Alternatively, open
that file directly in your browser.

The project uses CDN-hosted libraries, so an internet connection is
required for external resources such as Tailwind CSS, Font Awesome,
Google Fonts, and html2canvas.

## How to Use

1.  Open the planner in your browser.
2.  Add a course and enter its details.
3.  Select the appropriate VIT FFCS slot combination.
4.  For laboratory courses, choose the relevant classification and link
    it to a theory course or another lab session when required.
5.  Save the course and review its placement in the timetable.
6.  Use separate drafts to try alternative course and slot combinations.
7.  Compare drafts, review the course registry, and export the timetable
    when ready.

## Data and Privacy

The planner stores timetable state in the browser's local storage. Saved
drafts are associated with the browser and device you use. Clearing
browser data or local storage may remove saved timetable information.

This project does not require a user account or a server-side database.

## Intended Audience

This tool is designed around **VIT's FFCS slot allocation system** and
is intended for VIT students. Its slot mappings and clash checks should
not be assumed to apply to other universities.

## Limitations

-   The planner is an independent planning aid, not an official VIT
    registration system.
-   It does not register courses or verify live course availability.
-   Students should cross-check their final selections with the official
    VIT FFCS portal and current university instructions.

## Contributing

Suggestions, bug reports, and improvements are welcome. You can open an
issue or submit a pull request through GitHub.

## License

No license has been specified yet. Unless a license is added to this
repository, the default copyright rules apply and reuse, modification,
and redistribution are not automatically granted.
