# find-findIndex

Exercises using find() and findIndex()


## `find` and `findIndex`
* `find()` finds the first element in an array that meets a condition
* Returns the first value if found or undefined if value isn't found
```js
const scores = [0, 0, 0, 0, 68, 75, 83, 85, 89, 93, 95]

scores.find(function(score) {
	return score > 75
})
// 83
```
* `findIndex()` is essentially the same as `find()`, only it returns the index instead
```js
const scores = [0, 0, 0, 0, 68, 75, 83, 85, 89, 93, 95]

scores.findIndex(function(score) {
	return score > 0 && score % 2 === 0
})
// 4
```