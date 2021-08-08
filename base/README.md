`Base`
1. go run .
    运行程序
2. go build xxx.go
    编译 go 文件

`Structure`
1. 包声明
    package main
2. 引入包
    import "fmt"
3. 函数
    func main() {
	表达式
    }
4. 变量  
    1. var identifier type
    2. var identifier1, identifier2 type
    3. 变量声明 + 初始化
        ```
        s = ""
        var s string
        var s = ""
        var s string = ""
        ```
5. 语句 & 表达式
6. 注释
    1. 单行 
        //
    2. 多行
        /*
	     注释
	    */

`Keywords`
```
    break       default         func    interface   select
    case        defer           go      map         struct 
    chan        else            goto    package     switch
    const       fallthrough     if      range       type   
    continue    for             import  return      var 
```

`Predefined identifier`
```
    内建常量：
        true false iota nil

    内建类型：
        int int8 int16 int32 int64
        uint uint8 uint16 uint32 uint64 uintptr
        float32 float64 complex128 complex64
        bool byte rune string error
    
    内建函数：
        make len cap new append copy close delete
        complex real imag
        panic recover
    
    append      bool            byte    cap         close
    complex64   complex128      unit16  copy        false
    float32     float64         imag    int         int8
    int16       uint32          int32   int64       iota
    len         make            new     nil         panic
    uint64      print           println real        recover
    string      true            uint    uint8       uintptr
```
