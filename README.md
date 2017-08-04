# cpp-vars
C++ var type like php

# Usage
```c++
//string
var test = "test";
echo(test);

//numbers
var integer = 2;
echo( integer );

//define array
var array;
array[0] = "test";
array["ppp"] = 11.23;


print_r( array );
//foreach
for( auto &x : array ) {
  print_r( array[x] );
  print_r( x );
}


//get string 
std::cout << array[0].string();

//get number value or use .to_int() to get int value
std::cout << array["ppp"].to_num() << std::endl;

//all operator supported
var a = 10;
a += 2;
echo( a );

//logical operator supported
var aa = 2;
var bb = 3;
echo( aa && bb );

var list = { "test", 1, 2.2 };
print_r( list );

var ppp = var({
	{"test1", "test1"},
	{"test2", "test2"},

}).to_kv();

print_r( ppp );
  
```

# Build
```
g++ -std=c++11 test.cpp -o test
```

# My packages
also see another package that writed with this class for easy usage & developes

1. [4php ](https://github.com/pejman-hkh/4php) ( Simple interpreter like php syntax in c++ )
2. [Sqlite c++ wrapper ](https://github.com/pejman-hkh/sqlite-cpp-wrapper)
3. [Mysql c++ wrapper](https://github.com/pejman-hkh/mysql-cpp-wrapper)

