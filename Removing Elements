using System;
using System.Linq;
using System.Collections.Generic;

  public static class Kata
    {
        public static object[] RemoveEveryOther(object[] arr)
        {
          // Go through the array with looking at each element AND it's index
          var everyOtherElement = arr.Where((element, index) => index % 2 == 0).ToArray();
          return everyOtherElement;     
        }
    }
