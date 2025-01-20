# LiteJS-framework
This is a component-based UI framework written in simple JavaScript. It allows you to quickly bind JavaScript content into HTML in HTML DOM syntax.

## Usage:
### Step 1: Link LiteJS framework in your code:
```
   <script defer src="http://samannoyb.me/LiteJS-framework/App.js"></script>
```

### Step 2: Create a "returnObject" variable in your JavaScript and define it as an array:
```
 const returnObject = {    /* Example code, you can change the data but dont change the variable name lol */
        name: 'Samannoy Bhattacharjee',
        age: '13',
        school: 'abs'
    }
```
### Step 3: Create a <lite> tag in your HTML and bind your "returnObject" elements with a {{}} in it:
```
<lite>{{name}}</lite> /* Output: Samannoy Bhattacharjee */
<lite>{{age}}</lite> /* output: 13 */
<lite>{{school}}</lite> /*output: abs */
```

That's it, and you got a way simpler alternative to React and all.... I am looking forward to publishing a npm package of this too so NodeJS can be directly used!
Specially built for [HighSeas](https://highseas.hackclub.com/)

## Thanks!

