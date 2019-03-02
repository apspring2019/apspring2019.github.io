## Arrays:
* Simple example with array (if needed)
* Arrays initialization:
    * Using for loop
    * At declaration time
    * `Arrays.fill`
    * `Arrays.copyOf` & `Arrays.copyOfRange`
    * `Arrays.setAll` (JDK 8, in the future)
* Arrays class:
    * `Arrays.asList`
    * `Arrays.equals`
    * `Arrays.sort`
    * `Arrays.toString`
    * `Arrays.binarySearch`
    * ...
* ArrayList
    * `add`
    * `get`
    * `size`
    * `isEmpty`
    * `remove`
    * `toArray`
    * ...



## Strings:
* Useful methods:
    * `charAt`
    * `concat` (difference between concat and plus operator)
    * `contains`
    * `startsWith` & `endsWith`
    * `equals` & `equalsIgnoreCase` **
    * `format`
    * `indexOf` & `lastIndexOf`
    * `length`
    * `isEmpty` (a clean code technique) (🤓is null or empty)
    * `substring`
    * `join` (iterable? arrays are iterable, other iterables will be found out soon)
    * `trim` (trimStart & trimEnd??)
    * `toUpperCase` & `toLowerCase`
    * `valueOf`
    * (🤓`getBytes`)
* `String.format`
* Checking equality of strings
* (🤓`intern`)
* Regex
    * Grammar and Notations
    * `matches`
    * `replaceAll` & `replaceFirst`
        * `trimStart` & `trimEnd` implementation
    * `split`
    * `Pattern`
    * `Match`
    * Groups & Captures
* Immutable (🤓Why? security and performance)
    * Frequent manipulation? `StringBuilder` (& 🤓`StringBuffer`)