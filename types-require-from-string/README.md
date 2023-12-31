# Installation
> `npm install --save @types/require-from-string`

# Summary
This package contains type definitions for require-from-string (https://github.com/floatdrop/require-from-string).

# Details
Files were exported from https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/require-from-string.
## [index.d.ts](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/require-from-string/index.d.ts)
````ts
// Type definitions for require-from-string 1.2
// Project: https://github.com/floatdrop/require-from-string
// Definitions by: Ika <https://github.com/ikatyang>
// Definitions: https://github.com/DefinitelyTyped/DefinitelyTyped

/**
 * Load module from string in Node.
 */
declare function requireFromString(code: string, options?: requireFromString.Options): any;
declare function requireFromString(code: string, filename?: string, options?: requireFromString.Options): any;

declare namespace requireFromString {
    interface Options {
        /**
         * List of `paths`, that will be appended to module `paths`.
         * Useful when you want to be able require modules from these paths.
         */
        appendPaths?: string[] | undefined;
        /**
         * List of `paths`, that will be preppended to module `paths`.
         * Useful when you want to be able require modules from these paths.
         */
        prependPaths?: string[] | undefined;
    }
}

export = requireFromString;

````

### Additional Details
 * Last updated: Wed, 07 Jul 2021 18:02:24 GMT
 * Dependencies: none
 * Global values: none

# Credits
These definitions were written by [Ika](https://github.com/ikatyang).
