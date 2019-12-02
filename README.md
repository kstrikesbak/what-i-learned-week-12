# **WHAT I LEARNED IN  WEEK 12** 
___

    It's Week 12. Time is flying 
    Tell JK I'm still Rowling. - Kejal


## `oops`

This was an intro to Object Orientated programming. 'this' is used to address the exact object we are talking about that. 

```javascript
const Stack = function() {
  return {
    items : [],
    add : function(str){
      return this.items.push(str);
    },
    remove : function() {
      return this.items.pop();
    },
    peek : function() {
      return this.items[this.items.length -1]
    }
  }
}

const Queue = function() {
    return {
      items : [],
      add : function(str){
        return this.items.push(str);
      },
      remove : function() {
        return this.items.shift();
      },
      peek : function() {
        return this.items[0]
      },
    }
  }

```

## `ToDOM`

Used DOM to make a to do app. 

## `ToDO-Two`

We worked in pairs and improved our To-Do apps with new features.
We manipulated the Dom. However, it is better to use arrays as then the data can later be used. 

## `Componentize`

We were introduced to several websites that adds CSS to our sites. This allows programmers to focus on the code rather than worry about the front end.

* Bootstrap

* Semantic UI

* Materialize

* Bulma