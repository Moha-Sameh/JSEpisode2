# JavaScript Episode 1

In this exercise your objective will be to write a `pairs()` function.

`pairs()` has the following features:

* It accepts an array of names: `pairs(['Asis', 'Hamsa', 'Fawas', 'Mishmish'])`  
    
* It returns a randomized pairing of the people in the list: `[['Mishmish', 'Asis'], ['Fawas', 'Hamsa']]`
    
* It can handle an odd number of names: `pairs(['Asis', 'Hamsa', 'Fawas', 'Mishmish', 'Hussein])` returns `[['Mishmish', 'Fawas'], ['Asis', 'Hussein'], ['Hamsa']]`

* It returns an empty array if it gets passed nothing: `pairs()` returns `[]`

## Instructions

#### Tools

* Install `node`:
  ```bash
  $ brew install node
  ```
* Install `yarn`:
  ```bash
  $ npm install -g yarn
  ```
  
#### The Files

Clone this repository (make sure you clone it into your `development` directory):

```bash
$ git clone https://github.com/JoinCODED/JSEpisode1.git
```

Inside you'll find two `.js` files:

* `pairs.js` - this is the file you'll be editing
* `pairs.spec.js` - this is a testing file. It checks that your `pairs()` function has the features discussed above.   
  **DO NOT EDIT THIS FILE**

#### Running The Tests

Install all the requirements:

  1. Navigate to the project root (you'll find a file called `package.json` there).
  2. Install the requirments using `yarn install`.
  
Run the tests:

```bash
$ yarn test -- --watch
```

This command will run the testing file and test your `pairs()` function to make sure it has all the required features.  
The tests will keep running every time you make changes to `pairs.js`.  
To exit the test-runner hit `ctrl+C`.

You'll know when you're done when your code passes all the tests.
