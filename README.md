# Molohooks

only 2 hooks, mainly for my personal use

## Hooks

### useToggler

For boolean state

Params

1. `defaultValue: boolean` : Default value for the state

Returns

1. `value: boolean` : The value of the state
1. `setTrue: () => void` : Set the state to `true`
1. `setFalse: () => void` : Set the state to `false`
1. `toggler: () => void` : Toggle the state

### useInputHandler

For controlled input handler

Params

1. `defaultValue: string` : Default value for the state

Returns

1. `value: boolean` : The value of the state
1. `handleChange: (e: ChangeEvent<HTMLInputElement>) => void` : Handler for onChange event on input element
1. `clearValue: () => void` : Set the value to an empty string (`''`)
