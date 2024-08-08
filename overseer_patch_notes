## Application Update - v0.1.13

Date: 07-24-2024

## **New Features**

- **Conditional Access Policies**: The application can now *properly* display the conditional access policies present within a tenant.
- **Overwatch**: The application now displays lists of keys used to provide Supabase access to other services. (*Original Overseer python class*)
- **User Phishing Coverage**: The application now displays a list of compromised users and how many times they were compromised + what methods they were compromised by.

## **Improvements**

- **DynamicTable Functionality**: The DynamicTable component now support links and has received improved updates to the CSV export options. JSON exports are available, just need to add the button.

## **Bug Fixes**

- **Persistent Themes**: My knowledge was advanced when I learned that `localStorage` and `sessionStorage` only exist within the context of the tab. Need to look into using cookies for themes and such if I want that much functionality, could also add to middleware but eh.

---

## **Known Issues**

- **Flicker on changing Parent Layouts**: On some page transitions, during unload the viewport will fly over the navbar instead of underneath. I need to address swapping LayoutTransition components on separate trees. Currently in question: `/gatekeeper` `/(secure)`
- **Check XSS on Toast Component**: Need to make sure content is sanitized in the URL when supplying the Toast component `/app/layout.tsx`

---

Thank you for using Kobargo Overseer. If you have any questions or feedback, please reach out to Zack <zhatch@kobargo.com> & <dev@kobargo.com>


## Application Update - v0.1.12

Date: 07-09-2024

## **New Features**

- **Stored Theme**: The application will now save the selected theme to localStorage in browser and apply it on subsequent visits.
- **Dynamic Table Sorting and Exporting**: The DynamicTable component commonly found throughout the application now support column-based sorting and exporting the table as csv.
- **Redirect after SignOut**: After users are signed out of a route they can no longer access, they are redirected back where they came from with a small toast informing the user.

## **Improvements**

- **DynamicTable Functionality**: The DynamicTable component can also support copy to clipboard and other delimeters

## **Bug Fixes**

- **Toasts not supported**: Toasts were not correctly displayed when the correct URL parameter was supplied.

---

## **Known Issues**

- **Flicker on changing Parent Layouts**: On some page transitions, during unload the viewport will fly over the navbar instead of underneath. I need to address swapping LayoutTransition components on separate trees. Currently in question: `/gatekeeper` `/(secure)`
- **Check XSS on Toast Component**: Need to make sure content is sanitized in the URL when supplying the Toast component `/app/layout.tsx`

---

Thank you for using Kobargo Overseer. If you have any questions or feedback, please reach out to Zack <zhatch@kobargo.com> & <dev@kobargo.com>

