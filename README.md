# React People Table (Advanced) - Filterging and Sorting

[DEMO LINK](https://nazarbaraban.github.io/react_people-table-advanced/) 


1. **Persistent URL Parameters:**
   - Saved all filter and sort parameters as URL Search Params, allowing for easy sharing of specific views.
   
2. **Retained Parameters on Navigation:**
   - Maintained search parameters when navigating within the `People` page, ensuring consistency in the displayed data.

3. **Conditional Sidebar Display:**
   - The sidebar with filters now appears only when people data is loaded, improving the user experience.

4. **NameFilter Functionality:**
   - Implemented the `NameFilter` to update the `query` search param with input text.
   - Filters people based on a case-insensitive match with the `name`, `motherName`, or `fatherName`.
   - Ensured that the `query` search param is absent in the URL when the input is empty.

5. **CenturyFilter Enhancement:**
   - Enabled the selection of multiple centuries or all of them in the `CenturyFilter`.
   - Utilized `append` and `getAll` methods to manage the `centuries` search param.

6. **Sorting Capabilities:**
   - Implemented sorting by `name`, `sex`, `born`, and `died` by clicking on column headers.
   - Applied a three-click mechanism for sorting, including ascending, descending, and disabling sorting.
   - Utilized the `sort` and `order` search params to save sorting state.
   - Ensured that the URL does not contain `sort` and `order` search params when sorting is disabled.
