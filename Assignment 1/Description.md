# Assignment 1 : Web Assessment

Complete the online questions. 

A quesiton is given as a snippet of code with a missing section.

Example:

    class A {
      ?? 
    }
    
    public class Comprehension {
        public static void main(String[] arg){
            A a1 = new A();
            A a2 = new A(2);
            assert a2.equals(a1);
        }
    }

The user can only input code to fill the missing section. Certain questions have rules like not allowed to use the keyword *new*.

The example's solution:

    A(){}
    A(int i){}
    public boolean equals(A a){
      return true;
    }
