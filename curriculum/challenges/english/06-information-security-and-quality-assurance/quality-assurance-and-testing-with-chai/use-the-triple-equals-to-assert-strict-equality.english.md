---
id: 587d824b367417b2b2512c4b
title: Use the Triple Equals to Assert Strict Equality
challengeType: 2
---

## Description
<section id='description'>
As a reminder, this project is being built upon the following starter project on <a href='https://glitch.com/#!/import/github/freeCodeCamp/boilerplate-mochachai/'>Glitch</a>, or cloned from <a href='https://github.com/freeCodeCamp/boilerplate-mochachai/'>GitHub</a>.
<code>.strictEqual()</code>, <code>.notStrictEqual()</code>.
<code>.strictEqual()</code> compares objects using <code>'==='</code>.
</section>

## Instructions
<section id='instructions'>

</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: All tests should pass
    testString: getUserInput => $.get(getUserInput('url') + '/_api/get-tests?type=unit&n=5').then(data => {assert.equal(data.state,'passed'); }, xhr => { throw new Error(xhr.responseText); })
  - text: Choose the right assertion - strictEqual vs. notStrictEqual
    testString: getUserInput => $.get(getUserInput('url') + '/_api/get-tests?type=unit&n=5').then(data => {  assert.equal(data.assertions[0].method, 'notStrictEqual', 'with strictEqual the type must match'); }, xhr => { throw new Error(xhr.responseText); })
  - text: Choose the right assertion - strictEqual vs. notStrictEqual
    testString: getUserInput => $.get(getUserInput('url') + '/_api/get-tests?type=unit&n=5').then(data => {  assert.equal(data.assertions[1].method, 'strictEqual', '3*2 = 6...'); }, xhr => { throw new Error(xhr.responseText); })
  - text: Choose the right assertion - strictEqual vs. notStrictEqual
    testString: getUserInput => $.get(getUserInput('url') + '/_api/get-tests?type=unit&n=5').then(data => {  assert.equal(data.assertions[2].method, 'strictEqual', '6 * \'2\' is 12. Types match !'); }, xhr => { throw new Error(xhr.responseText); })
  - text: Choose the right assertion - strictEqual vs. notStrictEqual
    testString: getUserInput => $.get(getUserInput('url') + '/_api/get-tests?type=unit&n=5').then(data => {  assert.equal(data.assertions[3].method, 'notStrictEqual', 'Even if they have the same elements, the Arrays are notStrictEqual'); }, xhr => { throw new Error(xhr.responseText); })

```

</section>

## Challenge Seed
<section id='challengeSeed'>

</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
