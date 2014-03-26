Dexie.js
========
A bullet proof indexedDB wrapper.

 * The only indexedDB wrapper (so far) to support case insensitive search, set matching and logical OR operations.
 * Minimalistic and straight forward API, easy to use.
 * Bullet proof error handling using transaction scopes
 * Does not hide backend indexedDB from the caller - always possible to reach the backend IDB objects.
 * Performance focused
 * Portable across all browsers:
   * IE10+
   * Chrome
   * Firefox
   * Opera 15+
   * Android browser
   * Blackberry browser
   * Opera mobile 16+
   * Chrome for Android
   * Firefox for Android
   * IE Mobile
   * Safari (requires polyfill: http://nparashuram.com/IndexedDBShim/)
   * IOS Safari (requires polyfill: http://nparashuram.com/IndexedDBShim/)
 * Promise/A+ compliant
 * Code Completion friendly - Your IDE will guide you as you type!
 * Human readable queries: db.friends.where("lastName").anyOf("Helenius", "Fahlander").each(function(friend){...})
 * Extended key range queries: startsWith(), startsWithIgnoreCase(), equalsIgnoreCase(), anyOf([a,b,c,d,...])
 * Logical "OR": friends.where("age").below(40).or("length").above(200).toArray(...);
 * Built to be easily extended by 3rd part libraries
 * Simplified and robust error handling
 * Simplified upgrading framework
 * Thoroughly unit tested

Documentation
-------------
https://github.com/dfahlander/Dexie.js/wiki/Dexie.js

Download
--------
https://raw.githubusercontent.com/dfahlander/Dexie.js/master/dist/latest/Dexie.js
https://raw.githubusercontent.com/dfahlander/Dexie.js/master/dist/latest/Dexie.min.js


