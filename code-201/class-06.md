# Problem Domain, Objects, and the DOM

## JavaScript Object Basics

1. **How would you describe an object to a non-technical friend you grew up with?**

    In a general sense, think of an object like a collection. In its simplest terms it is a set of data and ways to work with data that can be grouped together. You can also use an object as a template for organizing and modifying data.

2. **What are some advantages to creating object literals?**

    Object literals are well suited to sending related and structured data more efficiently than sending them individually. Object literals are also easier to use and understand than an array.

3. **How do objects differ from arrays?**

    Objects are able to store both variables and functions, objects can be used to store and reference data by their object properties instead of the index of an array which when semantically labeled is easier to read

4. **Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**

    You would need to use bracket notation to access an object's property if it is stored in a variable.

5. **Evaluate the code below. What does the term this refer to and what is the advantage to using this?**

    `this` is a keyword that refers to the current object being referenced by the code. In the code below `this` is referring to the particular instance of the object "dog" to log the dog's name and age to the console which would be "Spot" and "14". `this` is helpful for writing code that can be used on every object created by a shared object definition.

    ```js
    const dog = {
      name: 'Spot',
      age: 2,
      color: 'white with black spots',
      humanAge: function (){
        console.log(`${this.name} is ${this.age*7} in human years`);
      }
    }
    ```

## Introduction To The DOM

1. **What is the DOM?**

    The DOM , or **D**ocument **O**bject **M**odel, is a programming interface for web documents and a representation of all the objects that makeup a web document.

2. **Briefly describe the relationship between the DOM and JavaScript.**

    The DOM is not written in JavaScript and JavaScript does not require the DOM in order to function. You can use JavaScript to access the DOM and add dynamic content to a web document.

## Things I want to know more about

- A better understanding of when and why I would need to use bracket notation to access an objects properties

## References

- [MDN: JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
- [Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
