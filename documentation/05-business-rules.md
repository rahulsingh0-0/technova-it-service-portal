# Business Rules

## Objective

Configure Business Rules to automate server-side actions when records are inserted or updated.

## Business Rule Types

The project demonstrates the following execution timings:

- Before
- After
- Async

## Before Business Rule

A Before Business Rule executes before the record is saved.

It can be used to:

- Validate data
- Set field values
- Prevent invalid updates
- Modify the current record

## After Business Rule

An After Business Rule executes after the record has been saved.

It can be used when an action needs to occur after the database operation, such as creating or updating a related record.

## Async Business Rule

An Async Business Rule runs in the background after the record is saved.

This is useful for processing that does not need to make the user wait for completion.

## Scripting Concepts

The project demonstrates basic server-side scripting concepts including:

- `current`
- `previous`
- `gs`
- `GlideRecord`
- Conditions
- `current.setValue()`
- `current.setAbortAction(true)`

## Testing

Business Rules were tested by creating and updating records and verifying that the expected server-side actions occurred.

## Skills Demonstrated

- Business Rule configuration
- Server-side scripting fundamentals
- Execution timing
- Record validation
- Basic GlideRecord usage
- Testing and troubleshooting
