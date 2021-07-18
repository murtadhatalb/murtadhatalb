1-my Solve the first question in Kotlin on the codesignal website

fun add(param1: Int, param2: Int): Int {
    
    return param1+ param2
}

2-my Solve the second question in Kotlin on the codesignal website

fun  centuryFromYear(year : Int): Int {
    

    
        return (year-1)/100 + 1
        
}

3-The solution to the third question in the Kotlin language on the codesignal website

fun checkPalindrome(inputString: String): Boolean =inputString.equals(inputString.reversed())


4-The solution to the fourth question in the Kotlin language on the codesignal website

fun adjacentElementsProduct(inputArray: MutableList<Int>): Int =(0..inputArray.size -2).map{
    
    inputArray[it]*inputArray[it+1]
}.max()?:Integer.MIN_VALUE

5-The solution to the fifth question in the Kotlin language on the codesignal website

fun shapeArea(n: Int): Int {
   
    return 2*n*(n-1) +1
  
}

6-The solution to the sixth question in the Kotlin language on the codesignal website

    fun makeArrayConsecutive2(statues: MutableList<Int>): Int {
  
  return statues.max()!!-statues.min()!!-statues.size+1


}

7-The solution to the seventh question in the Kotlin language on the codesignal website

    fun almostIncreasingSequence(sequence: MutableList<Int>): Boolean {
    
    var a=-1
    var b=0
    for(i in 1 until sequence.size)
    if(sequence[i-1]>=sequence[i])
    {
        a=i
        b++
    }
  if(b>1){
      return false
      
  }
  if(b==0){
      
      return true
  }
  if(a==sequence.size-1|| a==1){
      
      return true
  }
  if(sequence[a-1]<sequence[a+1]){
      return true
  }
  
  if(sequence[a-2]<sequence[a])
  {
      return true
  }
  return false
  
}

8-The solution to the eighth question in the Kotlin language on the codesignal website

fun matrixElementsSum(matrix: MutableList<MutableList<Int>>): Int {
    
    var total = 0
    for(i in 0 until matrix[0].size)
    for(j in 0 until matrix.size){
        if(matrix[j][i]==0){
            
        break;    
        
    }else{total+=matrix[j][i]}
    
    
}

return total
  
}

    
