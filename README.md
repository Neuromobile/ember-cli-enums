# ember-cli-enums

Creates enumerators for Ember projects.

## Installation

Install this addon via ember-cli:

```
ember install ember-cli-enums
```

## Usage

Use the following command to create a new enumerator:

```
ember g enum <name>
```

It creates it in the folder `enum/` with the following structure:

```
export default Object.freeze([
  {
    // example of an element of the enumerator
    label: 'Label',
    value: 'value',
  },
]);
```

## Development

### Installation

* `git clone <repository-url>` this repository
* `cd ember-cli-enums`
* `npm install`

### Running

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Running Tests

* `npm test` (Runs `ember try:each` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

### Building

* `ember build`

For more information on using ember-cli, visit [https://ember-cli.com/](https://ember-cli.com/).
