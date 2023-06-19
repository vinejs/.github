## A highly performant library to validate data in Node.js applications

VineJS is a framework agnostic validation library for Node.js. If you are looking for a type-safe and feature-rich validation library, VineJS might be it.

## Features

- **Type-safe**: Alongside runtime validations, the validated output in VineJS is completely type-safe.
- **50+ validation rules**: We ship with an ever-growing massive collection of validation rules.
- **13 schema types**: Use in-built schema types or create a custom one to represent the core data types of your application.
- **Support for custom messages**: First-class workflow for defining custom error messages.
- **Unions for conditional validation**: Unions in VineJS are built for writing conditional validations. For example: Ask for `appointment_date` when `has_appointment` is true. Also, the output is type-safe.
- **Error reporters**: Structure the errors using custom error reporters.

## Why VineJS?

- **Performance** - VineJS is built around performance. It is 5x-10x faster than Zod and Yup.
- **Built for validating form data and JSON payloads** - VineJS handles the [HTML forms serialization quirks](https://vinejs.dev/docs/html_forms_and_surprises) so that you never have to perform data normalization yourself.