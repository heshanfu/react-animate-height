# Changelog

### v2.0.4

15.08.2018.

**Refactored**

* Added `isPercentage` helper function.

-----

### v2.0.3

12.07.2018.

**Fixed**

* Fixed small bug introduced with 2.0.0 - In `componentDidMount`, `this.state` was used instead of `prevState`
* Content is not being hidden if set height is `auto`

-----

### v2.0.2

11.07.2018.

**Fixed**

* Fixed type script definitions file

-----

### v2.0.0 and v2.0.1

20.05.2018.

**Changed**

* Replaced `componentWillReceiveProps` by `componentDidUpdate` to address changes introduces with React v16.3

-----

### v1.0.4

20.05.2018.

**Changed**

* Enabled react v16.3+ in peer dependencies until react-animate-height v2 is out

-----

### v1.0.3

20.05.2018.

**Changed**

* Moved helpers outside of component to make component lighter
* Updated few dependencies

-----

### v1.0.2

21.04.2018.

**Added**

* Added `delay` prop, kudos to @quagliero [#51](https://github.com/Stanko/react-animate-height/pull/51)
* Changelog

-----

### v1.0.1

30.03.2018.

**Fixed**

* `animateOpacity` prop was passed directly to the `div` element, omitted it

-----

### v1.0.0

30.03.2018.

**Added**

* `animateOpacity` prop which fades content in or out depending on animation direction

**Changed**

* Removed unused vendor prefixes for `translate`

-----

For changes prior version 1.0.0 please check the [commit list](https://github.com/Stanko/react-animate-height/commits/master).
