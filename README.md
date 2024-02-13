#code for To Be Or Not To Be from leetcode practiceset
var expect = function(val1) {
    return myObj={
        toBe:function(val2){

            if(val1===val2){
                return true;
            }
            else{
                  throw new Error("Not Equal");
            }

        },
        notToBe:function(val2){

            if(val1!==val2){
                return true;
                 }
            else{
                throw new Error("Equal");
            }
        }
    }  
};
