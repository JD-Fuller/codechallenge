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


    <h3>TITLE</h3>  <h3>Challenge: 3</h3>
  <p>
  BODY
  
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
