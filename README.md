# marko-select

Select Input control for [MarkoJS](https://markojs.com)

## Installation

```
npm install marko-select
```
 or 

```
yarn add marko-select
```

Then use it in your app:

## Usage

```marko

<Select class="my-select-input"
        inputClass="form-control"
        menuClass="animated faster slideInDown"
        name="country"
        value=state.selectedCountry
        placeholder="Select Country"
        searchable=true
        options=[
          label: "United State", value: "US",
          label: "France", value: "FR"
        ]
        on-change("onHandlerChange")/>
```

## Inputs Properties

Common props you may want to specify include:

- `class` - apply a class to the control container
- `inputClass` - apply a class to the control input
- `menuClass` - apply a class to the control options menu
- `disabled` - disable the control
- `autoFocus` - focus the control when it mounts
- `searchable` - allow the user to search for matching options
- `name` - generate an HTML input with this name, containing the current value
- `options` - specify the options the user can select from
- `placeholder` - change the text displayed when no option is selected
- `value` - control the current value

## Events

- `on-change` - subscribe to select change events
- `on-menu-open` - subscribe to menu open events
- `on-menu-close` - subscribe to menu close events

Feedback & Contribution
-------

You know the say: No one is whole alone! So, feedbacks are all welcome. Kindly report any encounted [Issues here][] and I'll be glad to work on it right away. Thank you.


License
-------

This software is free to use under the MIT license. See the [LICENSE file][] for license text and copyright information.


[LICENSE file]: https://github.com/fabrice8/marko-intl-tel-input/blob/master/LICENSE
[Issues here]: https://github.com/fabrice8/marko-intl-tel-input/issues
