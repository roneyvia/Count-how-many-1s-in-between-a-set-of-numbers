# Count-how-many-1s-in-between-a-set-of-numbers
This js program will count number of 1s in between 1-15

```javascript
function myTotalOnes(){
  var count=0;
  for(var n=0;n<=15;n++){    
      var l=n.toString().length;
      var j=l;
      var k=l;
      for (var i = 1; i <= l; i++) {
         j = j-1; 
          if(n.toString().substring(j,k) == 1){
               count++;          
          }
          k--;
      }
  }
  console.log("Total Number 1s in between 1 to 15= "+count);
}
```
