# amplify-form-field



<!-- Auto Generated Below -->


## Properties

| Property        | Attribute        | Description | Type                                                 | Default     |
| --------------- | ---------------- | ----------- | ---------------------------------------------------- | ----------- |
| `fieldId`       | `field-id`       |             | `string`                                             | `undefined` |
| `hint`          | `hint`           |             | `string`                                             | `undefined` |
| `inputProps`    | --               |             | `{ type?: string; onInput?: (Event: any) => void; }` | `{}`        |
| `label`         | `label`          |             | `string`                                             | `undefined` |
| `styleOverride` | `style-override` |             | `boolean`                                            | `false`     |


## Dependencies

### Used by

 - [amplify-sign-in-password-field](../amplify-sign-in-password-field)
 - [amplify-sign-in-username-field](../amplify-sign-in-username-field)

### Depends on

- [amplify-label](../amplify-label)
- [amplify-text-input](../amplify-text-input)
- [amplify-hint](../amplify-hint)

### Graph
```mermaid
graph TD;
  amplify-form-field --> amplify-label
  amplify-form-field --> amplify-text-input
  amplify-form-field --> amplify-hint
  amplify-sign-in-password-field --> amplify-form-field
  amplify-sign-in-username-field --> amplify-form-field
  style amplify-form-field fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*