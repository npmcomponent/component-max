*This repository is a mirror of the [component](http://component.io) module [component/max](http://github.com/component/max). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-max`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# max

  Max value utility

## Installation

    $ component install component/max

## API

### max(array)

  Return the max value in `array`:

```js
max([1,5,6,1,2,0])
```

### max(array, fn)

  Max value in `array` with callback `fn(val, i)`:

```js
var age = max(users, function(u){ return u.age })
```

### max(array, string)

  Max value in `array` with the given property `string`:

```js
var age = max(users, 'age')
```

# License

  MIT
