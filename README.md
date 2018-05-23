# Q.TwoStringInputAndOutputSameTwoString


## *문자열 두 개를 입력받아 두 문자열이 같은지 여부를 판단해주는 함수*

````
func sameTwoReturn(one: String, two: String) {
    if one == two { 
        print("\(one)와 \(two)는 같습니다.")
    } else {
        print("\(one)와 \(two)는 다릅니다.")
    }
}
sameTwoReturn(one: "1", two: "2")
sameTwoReturn(one: "전지현", two: "김하늘")
sameTwoReturn(one: "나", two: "나")
````
````
func checkStr(_ Str1:String,_ Str2:String){
    if Str1==Str2{
        print("true")
    }
    else{
        print("false")
    }
}
checkStr("apple", "e")
````
````
func getString(str: String ,str2: String) -> Bool{
    return str == str2 ? true : false
}
getString(str: "a", str2: "a")
````
