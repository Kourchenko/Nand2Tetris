# Nand2Tetris
##### Source for project: [Nand2Tetris by Noam Nisan and Shimon Schocken](www.nand2tetris.org)


###Building a modern computer.

The basis of this project is the Nand Gate, which returns 0 if and only if all inputs are equal to 1. 
From the Nand Gate, we can create NOT, AND, OR, XOR, MUX(Multiplexer), DMUX(Demultiplexer), and various other logic gates. Understanding logic gates helps us create computers and programs.
  
#####Nand Gate defined:
* Python  
  ```python
    def nand(a, b):
      if a==b==1:
          return 0
      return 1

  ```
* Java
```java
public class bunnyEars2 {
    public int Nand(int a, int b) {
        if (a == 1 && b == 1) {
            return 0;
        }
        return 1;
    }    
}
```

### Installation available for Mac and Windows

http://www.nand2tetris.org/software.php



