const secondMax = (arr) => {
    let max;
    if(arr.length == 1) {
        return Math.max(arr)
    }else if(arr.length > 1) {
        max = arr.sort(function(a, b){return a - b}).pop()
        while(arr.length > 1) {
            
            if(max == Math.max(...arr)) {
                max = arr.sort(function(a, b){return a - b}).pop();
               /* if(max != Math.max(...arr)) {
                    return Math.max(...arr);
                }
                */
            } else {
                return Math.max(...arr)
            }
            
        }
        return Math.max(...arr)        
    } else {
        return ('Error!')
    }
}
  let arr = [9,9,9,9,9,9,9,5,4,10];
  const ans = secondMax(arr);
  console.log(ans);
