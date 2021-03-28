# conway
Conway "Game of Life."  Learning Python.

```
$ ./dunc_conway.py -h
usage: dunc_conway.py [-h] [-r ROWS] [-c COLS] [-l LIVING] [-m MAX] [-t TIME]

optional arguments:
  -h, --help            show this help message and exit
  -r ROWS, --rows ROWS  rows in matrix
  -c COLS, --cols COLS  cols in matrix
  -l LIVING, --living LIVING
                        initial living cell count
  -m MAX, --max MAX     max cycles, -1 = infinite
  -t TIME, --time TIME  time between each cycle in seconds

$ python3 -m doctest -v dunc_conway.txt
. . .

$ ./dunc_conway.py
cycle 0 : 200
     *           * *     * *     *           * *   *       *
     * * * *       *                         *       *      
             *   *   *           *                 *        
   *       *                         *   *               *  
                   *                 *         *           *
 * *                 * *   *             *         *   *    
                             * *       *     *              
     * *       * * *                                 *     *
   * *       *             *         *     *     *         *
         *     *           *               *         *      
             *     * *   *       * *     *   * *            
     *   * *       *       *         *         *            
 *       * *                     *       *                 *
             *                     *     *                 *
         *   *   *                       * *                
     *     *                         * *   *       *       *
     * *       *   *   *     *   *       *             * * *
               *   *   *         * *     *     * *     *    
           *   *           *   * *         * *              
     *             * * *   *   *           * * *     *     *
 *       *         *     *       *       *       *          
             *     *           *   *                        
     * *   * * *       *   *   *       *   *         *     *
   *           *   *   *       *     *   *   *             *
   *                   *           *       * *       *   *  
 * *     *     *   *       * * * *       *   *           *  
     * *         *             * *     *           *   * *  
 *   * *           * *           *       *     *            
 *       * *           *         *   *   *   *         *   *
 *         *   *               *     *       * *       *    
alive: 225
static: False
```