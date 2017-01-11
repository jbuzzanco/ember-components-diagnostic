# Ember Components Diagnostic

Record your responses inside the fenced code blocks below each question.

1.  Give an example of a visual hierarchy that could be modeled with components. Explain why each piece might be it's own component.

    ```md
    A list of quotes and within the list are different famous people who have quotes so say winston churchill's quotes are a component within the quotes component.
    ```

1.  What is the command to generate a new component called '`my-map`'?

    ```sh
ember generate component my-map
    ```

1.  What files are created and/or edited to produce a component, and what are their responsibilities?

    ```md
    I tried looking this up but couldn't find it. I think its the component file & template file are created, & the route is updated.
    The component tells what actions to do and or show. the template shows what will be on the front end. the route is updated in order
    to show where the data will be displayed
    ```

1.  Suppose you have a component '`my-contact`', which is loaded from
    '`app/contacts/template.hbs`' when visiting the `/contacts` route. What is
    the syntax (code that is written) to render this component inside that template?

    ```html
    {{#each list.contacts as |contact|}}
    {{/each}}
    ```

1.  Each contact has multiple phone numbers. Suppose you also have '`my-phone`'
    nested under '`my-contact`'. What is the code you would write in
    '`app/components/my-contact/template.hbs`' to load the nested component and
    pass it data?

    ```html
    ember generate component /my-contact/my-phone

    {{#each list.contact as |contact|}}
    {{/each}}


  -->
    ```
