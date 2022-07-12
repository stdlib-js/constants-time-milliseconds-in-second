<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Milliseconds in a Second

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Number of milliseconds in a second.



<section class="usage">

## Usage

```javascript
import MILLISECONDS_IN_SECOND from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-time-milliseconds-in-second@v0.0.8-deno/mod.js';
```

#### MILLISECONDS_IN_SECOND

Number of milliseconds in a second.

```javascript
var bool = ( MILLISECONDS_IN_SECOND === 1000 );
// returns true
```

</section>

<!-- /.usage -->

<section class="notes">

## Notes

-   The value is a generalization and does **not** take into account inaccuracies arising due to complications with time and dates. 

</section>

<!-- /.notes -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
import randu from 'https://cdn.jsdelivr.net/gh/stdlib-js/random-base-randu@deno/mod.js';
import roundn from 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-roundn@deno/mod.js';
import MILLISECONDS_IN_SECOND from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-time-milliseconds-in-second@v0.0.8-deno/mod.js';

var ms;
var s;
var i;

function secs2ms( secs ) {
    return secs * MILLISECONDS_IN_SECOND;
}

for ( i = 0; i < 10; i++ ) {
    s = roundn( randu()*20.0, -2 );
    ms = secs2ms( s );
    console.log( '%d seconds => %d milliseconds', s, ms );
}
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-time-milliseconds-in-second.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-time-milliseconds-in-second

[test-image]: https://github.com/stdlib-js/constants-time-milliseconds-in-second/actions/workflows/test.yml/badge.svg?branch=v0.0.8
[test-url]: https://github.com/stdlib-js/constants-time-milliseconds-in-second/actions/workflows/test.yml?query=branch:v0.0.8

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-time-milliseconds-in-second/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-time-milliseconds-in-second?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-time-milliseconds-in-second.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-time-milliseconds-in-second/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-time-milliseconds-in-second/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-time-milliseconds-in-second/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-time-milliseconds-in-second/tree/esm
[branches-url]: https://github.com/stdlib-js/constants-time-milliseconds-in-second/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-time-milliseconds-in-second/main/LICENSE

</section>

<!-- /.links -->
