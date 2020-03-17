<template>
  <h1>WhiteBoard Area</h1>
  <h2>Holding Place until database is established - we will utilize a v-for for this component<h2>
  
  <h3>TITLE</h3>
  <p>
  BODY
  
  </p>
  <h4></h4>
  <p>SOLUTION</p>
  
  
    <h3>Challenge: 1</h3>
    <p><strong>Given an array of integers, find the sum of its elements.

For example, if the array <code> ar = [1,2,3]</code> ,<code> 1 + 2 + 3 = 6 </code> , so return <code> 6</code>.</p>
  <p>
  BODY
  
  </p>
  <h4></h4>
  <p>SOLUTION</p>
  
  
    <h3>TITLE</h3>

 <h3>Challenge: 2 Palindrome</h3>

  <p>
  
  const palindrome = str => {
  // turn the string to lowercase
  str = str.toLowerCase()
  // reverse input string and return the result of the
  // comparisong
  return str === str.split('').reverse().join('')
}
  </p>
  
  
  <h4></h4>
  <p>SOLUTION</p>
    <h3>FizzBuzz</h3>
  <p>
  const fizzBuzz = num => {
  for(let i = 1; i <= num; i++) {
    // check if the number is a multiple of 3 and 5
    if(i % 3 === 0 && i % 5 === 0) {
      console.log('fizzbuzz')
    } // check if the number is a multiple of 3
      else if(i % 3 === 0) {
      console.log('fizz')
    } // check if the number is a multiple of 5
      else if(i % 5 === 0) {
      console.log('buzz')
    } else {
      console.log(i)
    }
  }
}
  </p>
  <h4></h4>
  <p>SOLUTION</p>


    <h3>Anagram</h3>  <h3>Challenge: 3</h3>
  <p>
  challenge:

// helper function that builds the
// object to store the data
const buildCharObject = str => {
  const charObj = {}
  for(let char of str.replace(/[^\w]/g).toLowerCase()) {
    // if the object has already a key value pair
    // equal to the value being looped over,
    // increase the value by 1, otherwise add
    // the letter being looped over as key and 1 as its value
    charObj[char] = charObj[char] + 1 || 1
  }
  return charObj
}

// main function
const anagram = (strA, strB) => {
  // build the object that holds strA data
  const aCharObject = buildCharObject(strA)
  // build the object that holds strB data
  const bCharObject = buildCharObject(strB)

  // compare number of keys in the two objects
  // (anagrams must have the same number of letters)
  if(Object.keys(aCharObject).length !== Object.keys(bCharObject).length) {
    return false
  }
  // if both objects have the same number of keys
  // we can be sure that at least both strings
  // have the same number of characters
  // Now we can compare the two objects to see if both
  // have the same letters in the same amount
  for(let char in aCharObject) {
    if(aCharObject[char] !== bCharObject[char]) {
      return false
    }
  }
  // if both the above checks succeed,
  // you have an anagram: return true
  return true
}
  
  </p>
  <h4></h4>
  <p>SOLUTION</p>


    <h3>TITLE</h3>  <h3>Challenge: 4</h3>
  <p>
  BODY
  
  </p>
  <h4></h4>
  <p>SOLUTION</p>


    <h3>TITLE</h3>  <h3>Challenge: 5</h3>
  <p>
  BODY
  
  </p>
  <h4></h4>
  <p>SOLUTION</p>
    <h3>TITLE</h3>
  <p>
  BODY
  
  </p>
  <h4></h4>
  <p>SOLUTION</p>
    <h3>TITLE</h3>
  <p>
  BODY
  
  </p>
  <h4></h4>
  <p>SOLUTION</p>  <h3>TITLE</h3>
  <p>
  BODY
  
  </p>
  <h4></h4>
  <p>SOLUTION</p>  <h3>TITLE</h3>
  <p>
  BODY
  
  </p>
  <h4></h4>
  <p>SOLUTION</p>
  
</template>

<script>
export default {
  name: "WhiteBoard"
};
</script>

<style></style>
