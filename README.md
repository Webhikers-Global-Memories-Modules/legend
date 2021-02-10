# legend

This is going to be a basic `component` that enables you to create and edit a list of `places`. 

You can `create`, `update`, and `delete` `place-items` in the list. No `API`, no database and no storage is required.

**no styling or css is required at all, we only need functionality for now!!**

1. Install a basic `Vue.js` application.
2. Install `bootstrap-vue`.
3. Create a basic `Vue.js component` and call it `places.vue`
4. In the `places.vue` dataset create an empty list of `places` and display it with a loop in the template.
5. One `place` has the following properties: `location`, `title`, `icon`, `color`.
6. Below the list-template add a button with `create` functionality to add a new `place`
7. When the `create` button is clicked, open a `bootstrap-vue` modal. The `modal` functionality details are listed below.
8. When you created a new place it should autamtically be displayed in the template section.
9. For each `place` list-item, show the title, a `delete` button and an `update` button.
10. When the `delete` button gets clicked remove the item from the list.
11. When the `update` button gets clicked, re-open the modal and prefill its content with the previously selected data.

Specifications of the modal:

1. In the `bootstrap-vue` modal add a `text input` with google maps places autocomplete functionality.
2. Restrict the google maps places autocomplete to find countries or small cities as the smallest entity. This will be the `location` property.
3. Add a simple text input. This will be the `title` property.
4. Add a select input with fake icon names. The icons do not exist yet and you can call them somthing like `icon-1`, `icon-2`, `icon-3`, etc...This will be the `icon` property.
5. Add a `Vue.js` color picker plugin of your choice and let users pick a color. This will be the `color` property.
