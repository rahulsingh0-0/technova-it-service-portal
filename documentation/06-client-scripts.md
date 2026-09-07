# Client Scripts

## Objective

Configure Client Scripts to control and validate form behavior on the client side.

## Client Script Types

The project demonstrates the following Client Script types:

- onLoad
- onChange
- onSubmit

## onLoad

Used to perform actions when a form loads.

Example use cases:

- Set default behavior
- Display information
- Control form fields

## onChange

Used when the value of a field changes.

Example use cases:

- Dynamically change field behavior
- Show or hide fields
- Make fields mandatory
- Validate user input

## onSubmit

Used when a user submits a form.

Example use cases:

- Validate form data
- Prevent submission when required conditions are not met

## Scripting Concepts

The project demonstrates basic client-side scripting using:

- `g_form`
- `g_form.getValue()`
- `g_form.setValue()`
- `g_form.setMandatory()`
- `g_form.setVisible()`
- `g_form.setReadOnly()`
- `g_form.addInfoMessage()`

## Testing

Client Scripts were tested directly on ServiceNow forms to verify that the expected behavior occurs when forms load, fields change, and records are submitted.

## Skills Demonstrated

- Client-side scripting
- Form behavior configuration
- Field validation
- Dynamic form customization
- Basic `g_form` usage
