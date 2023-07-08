# matrix+

Implementation of the matrix_oop.h library.


## 1. Implementation of the matrix_oop.h library functions

- Implement the matrix as an `Matrix` class
- Implement the operations described


`bool EqMatrix(const Matrix& other)`
`void SumMatrix(const Matrix& other)` 
`void SubMatrix(const Matrix& other)` 
`void MulNumber(const double num) ` 
`void MulMatrix(const Matrix& other)` 
`S21Matrix Transpose()` 
`S21Matrix CalcComplements()` 
`double Determinant()` 
`Matrix InverseMatrix()` 

`Matrix()` 
`Matrix(int rows, int cols) ` 
`Matrix(const Matrix& other)` 
`Matrix(Matrix&& other)`
`~Matrix()`

`+`
`-` 
`*` 
`==` 
`=`
`+=`
`-=`
`*=`
- Prepare full coverage of library functions code with unit-tests using the GTest library
